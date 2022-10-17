---
title: "USTC Combinatorics Group - Former Members"
layout: gridlay
excerpt: "USTC Combinatorics Group: Former Members"
sitemap: false
permalink: /former/
---

# Former Members
## Faculty
{% assign number_printed = 0 %}
{% for member in site.data.alumni_Faculty %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.duration }} <br> Role: {{ member.info }}</i>
  <ul style="overflow: hidden">

  </ul>
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

## Research Fellows and Visitors
<div class="row">
<div class="col-sm-6 clearfix">
<h4>Research Fellows</h4>
{% for member in site.data.alumni_ResearchFellows %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-6 clearfix">
<h4>Visitors</h4>
{% for member in site.data.alumni_visitors %}
{{ member.name }}
{% endfor %}
</div>

</div>

## Students
<div class="row">
<div class="col-sm-6 clearfix">
<h4>Ph.D students</h4>
{% for member in site.data.alumni_phd %}
{{ member.info }}
{% endfor %}
</div>

<div class="col-sm-6 clearfix">
<h4>Master students</h4>
{% for member in site.data.alumni_msc %}
{{ member.info }}
{% endfor %}
</div>

</div>
