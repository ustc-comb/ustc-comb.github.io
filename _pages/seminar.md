---
title: "USTC Combinatorics Group - Seminar"
layout: seminar
excerpt: "Combinatorics Seminar."
sitemap: false
permalink: /seminar/
---


# Combinatorics Seminar

## Latest

{% assign number_printed = 0 %}
{% for publi in site.data.seminar %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}
<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
<p><em>Date: </em>{{ publi.date }}</p>
<p><em>Abstract: </em>{{ publi.abstract }}</p>
  <p><em>Speaker: {{ publi.speakers }}</em></p>
  <p><strong>{{ publi.meeting.room }}<br>{{ publi.meeting.password }}</strong></p>
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



