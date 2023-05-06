---
title: "USTC Combinatorics Group - Workshops and Conferences"
layout: textlay
excerpt: "Combinatorics Workshops and Conferences."
sitemap: false
permalink: /workshops/
---


# Workshops and Conferences

{% for ws in site.data.workshops %}
<hr />
<p><font size="4" color="#6d9eeb"><strong>{{ ws.title | markdownify | remove: '<p>' | remove: '</p>' }}</strong></font><br><font size="3" color="#a5a5a5">{{ ws.date }}</font><br>{{ ws.place | markdownify | remove: '<p>' | remove: '</p>' }}</p>
<details>
{% if ws.banner %}
<div style="text-align:center;">
<img src="{{ ws.banner }}"  style="max-width: 100%; height: auto; width: auto; width: auto; max-height: 300px;">
</div>
{% endif %}
{{ ws.disc }}<br>
&nbsp;<br>
<strong>会议组织委员会 (Organizers): </strong><br>{{ ws.organizers }}<br>
</details>

{% endfor %}
<hr />