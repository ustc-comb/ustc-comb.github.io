---
title: "Teaching - USTC Combinatorics Group"
layout: seminar
excerpt: "Combinatorics Courses."
sitemap: ture
permalink: /teaching/
---


# Our Courses
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
  <p>{% if publi.meeting.room %}<strong>{{ publi.meeting.platform }}:&nbsp;</strong>{{ publi.meeting.room }}<br>{% endif %}{% if publi.meeting.password %}<strong>Passcode:&nbsp;</strong>{{ publi.meeting.password }}{% endif %}</p>
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

