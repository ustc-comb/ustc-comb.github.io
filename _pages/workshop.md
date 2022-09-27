---
title: "USTC Combinatorics Group - Workshops and Conferences"
layout: textlay
excerpt: "Combinatorics Workshops and Conferences."
sitemap: false
permalink: /workshops/
---


# Workshops and Conferences

{% for ws in site.data.workshops %}

<p><font size="5" color="#6d9eeb"><strong>{{ ws.date }} <br>
{{ ws.title | markdownify | remove: '<p>' | remove: '</p>' }}</strong></font><br><em>{{ ws.disc | markdownify | remove: '<p>' | remove: '</p>' }}</em></p>

{% endfor %}
