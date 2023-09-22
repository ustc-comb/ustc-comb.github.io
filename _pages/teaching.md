---
title: "Teaching"
layout: teaching
excerpt: "Combinatorics Courses."
sitemap: ture
permalink: /teaching/
---


# Our Courses
{% assign number_printed = 0 %}
{% for publi in site.data.courses %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}
<div class="col-sm-6 clearfix">
 <div class="well">
 <p><font size="5" color="green"><a href="{{ publi.webpage }}">{{ publi.title }}</a></font></p>
  <p><strong>Instructor:&nbsp;</strong><font size="4">{{ publi.instructor }}</font></p>
  <p><strong>Time:&nbsp;</strong>{{ publi.time }}</p>
  <p><strong>Place:&nbsp;</strong>{{ publi.place }}</p>

 </div>
</div>


{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p> &nbsp; </p>

