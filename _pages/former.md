---
title: "USTC Combinatorics Group - Former Members"
layout: gridlay
excerpt: "USTC Combinatorics Group: Former Members"
sitemap: false
permalink: /former/
---

# Former Members
<div class="row">

<div class="col-sm-4 clearfix">
<h4>Visitors</h4>
{% for member in site.data.alumni_visitors %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-4 clearfix">
<h4>Postdoctor</h4>
{% for member in site.data.alumni_postdoctor %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-4 clearfix">
<h4>Ph.D Students</h4>
{% for member in site.data.alumni_phd %}
{{ member.name }}
{% endfor %}
</div>
</div>

