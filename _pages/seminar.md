---
title: "USTC Combinatorics Group - Seminar"
layout: seminar
excerpt: "Combinatorics Seminar."
sitemap: false
permalink: /seminar/
---


# Combinatorics Seminar

<a href="{{ site.url }}{{ site.baseurl }}/feed.xml" style="float: right;"><img style="box-shadow: none; margin-top: 22px;" width="40px" src="{{ site.url }}{{ site.baseurl }}/images/rss.png"></a>

## Upcoming talks
{% assign postsBytitle = site.data.seminar | group_by_exp:"seminar","seminar.title" %}
{% for item in postsBytitle %}
{% if item.name == "TBA" %}
{% assign tba = item.items %}
{% endif %}
{% endfor %}

{% if tba %}
<div class="well">
<ul style="margin-bottom: 0px;">
{% for ftalk in tba %}
<li class="company" style="list-style-type: circle;">{{ ftalk.date }}, {{ ftalk.speakers }}. {{ ftalk.title }}.</li>
{% endfor %}
</ul>
</div>
{% endif %}

{% assign number_printed = 0 %}
{% for publi in site.data.seminar %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 and publi.title != "TBA" %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}
<div class="col-sm-6 clearfix">
 <div class="well">
 <p><font size="5" color="green">{{ publi.date }}: {{ publi.speakers }}</font></p>
  <pubtit><font size="4">{{ publi.title }}</font></pubtit>
<p><em><strong>Abstract: </strong></em>{{ publi.abstract }}</p>
  <p><strong>{{ publi.meeting.platform }}:&nbsp;</strong>{{ publi.meeting.room }}<br>{% if publi.meeting.password %}<strong>Passcode:&nbsp;</strong>{{ publi.meeting.password }}{% endif %}</p>
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>

 </div>
</div>


{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p> &nbsp; </p>

## Past talks



