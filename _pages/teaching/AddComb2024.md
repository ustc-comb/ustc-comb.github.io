---
title: "Additive and Extremal Combinatorics, Spring 24"
layout: textlay
excerpt: "Additive and Extremal Combinatorics, Spring 24"
sitemap: ture
permalink: /teaching/AddComb2024
---

# Additive and Extremal Combinatorics, Spring 24

<div class="col-sm-7">
## Instructor

- <a href="https://tuaentran.wixsite.com/homepage">Tuan Tran</a>

- Office: 1409, Management Building, East Campus

- E-mail: trantuan [at] ustc [dot] edu [dot] cn

## Time

Tuesday 15:55-18:20 and Thursday 14:00-15:35, in 5502 (the 5th teaching building).

## Lecture notes
{% for ln in site.data.teaching.AddComb2024.Lecturenotes %}
- {{ln.Note}}
{% endfor %}

## Presentation schedule
{% if  site.data.teaching.AddComb2024.Presentations%}
<table style="margin-left: auto; margin-right: auto; width: 100%; border:1px solid #e2e2e2;" border="1">
<tbody>
<tr style="border:1px solid #e2e2e2; text-align:center; font-weight: bold;">
<td style="border:1px solid #e2e2e2;">Date</td>
<td style="border:1px solid #e2e2e2;">Paper</td>
<td style="border:1px solid #e2e2e2;">Presenters</td>
</tr>
{% for pr in site.data.teaching.AddComb2024.Presentations %}
<tr style="border:1px solid #e2e2e2; text-align:center;">
<td style="border:1px solid #e2e2e2;">{{pr.Date}}</td>
<td style="border:1px solid #e2e2e2;">{{pr.Paper}}</td>
<td style="border:1px solid #e2e2e2;">{{pr.Presenters}}</td>
</tr>
{% endfor %}
</tbody>
</table>
{% else %}
To be announced.
{% endif %}


</div>

<div id="newsid" class="col-sm-5">
<div class="well">

<h3>Topics of the course</h3>
- Algebra methods
- Sunflowers and Kahn-Kalai conjecture
- Bollobas set-pairs inequality
- Sum-product problem
- Dependent random choice

<h3>Prerequisites</h3>
Linear Algebra, Graph Theory.
<h3>Requirements</h3>
Here you can read the <a href="#put your link heres"> requirements and formalities</a>
of the course.

<h3>Literature</h3>
Some of the lectures will mostly follow the two fantastic books listed below. Other lectures will be based on original papers.
<ul>
    <li> Laszlo Babai and Peter Frankl, Linear Algebra Methods in Combinatorics </li>
    <li> Yufei Zhao, Graph Theory and Additive Combinatorics: Exploring Structure and Randomness</li>
</ul>
</div>
</div>
