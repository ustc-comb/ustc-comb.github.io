---
title: "USTC Combinatorics Group - News"
layout: gridlay
excerpt: "News."
sitemap: false
permalink: /news
---

# News

{% for article in site.data.news %}
<p><font size="5">{{ article.date }} <br>
    <strong><em>{{ article.headline | markdownify | remove: '<p>' | remove: '</p>' }}</em></strong></font></p>
{% endfor %}