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
<h4>Faculty</h4>
{% for member in site.data.alumni_Faculty %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-4 clearfix">
<h4>Research Fellows</h4>
{% for member in site.data.alumni_postdoctor %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-4 clearfix">
<h4>Visitors</h4>
{% for member in site.data.alumni_visitors %}
{{ member.name }}
{% endfor %}
</div>

</div>

