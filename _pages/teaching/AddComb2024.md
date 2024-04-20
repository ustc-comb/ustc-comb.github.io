---
title: "Extremal and Additive Combinatorics, Spring 24"
layout: textlay
excerpt: "Extremal and Additive Combinatorics, Spring 24"
sitemap: ture
permalink: /teaching/AddComb2024
---

# Extremal and Additive Combinatorics, Spring 24

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

## Reading papers

1. Samuel Kutin, Constructing Large Set Systems with Given Intersection Sizes Modulo Composite Numbers. <a href="https://github.com/ustc-comb/ustc-comb.github.io/blob/gh-pages/downloads/Kutin.pdf">pdf</a>
1. Boris Bukh and Ting-Wei Chao, Sharp density bounds on the finite field Kakeya problem. <a href="https://github.com/ustc-comb/ustc-comb.github.io/blob/gh-pages/downloads/BC.pdf">pdf</a>
1. Christian Elsholtz, Laura Proske, and Lisa Sauermann, New lower bounds for three-term progression free sets in $F_p^n$. <a href="https://github.com/ustc-comb/ustc-comb.github.io/blob/gh-pages/downloads/EPS.pdf">pdf</a>
1. Matija Bucic, Shoham Letzter, Benny Sudakov, Tuan Tran. Minimum saturated families of sets. <a href="https://github.com/ustc-comb/ustc-comb.github.io/blob/gh-pages/downloads/BLST.pdf">pdf</a>
1. Asaf Shapira and Mykhaylo Tyomkyn, Weakly saturated hypergraphs and a conjecture of Tuza. <a href="https://github.com/ustc-comb/ustc-comb.github.io/blob/gh-pages/downloads/ST.pdf">pdf</a>
1. Benjamin Gunby, Xiaoyu He, Bhargav Narayanan, and Sam Spiro, Antichain Codes. <a href="https://github.com/ustc-comb/ustc-comb.github.io/blob/gh-pages/downloads/GHNS.pdf">pdf</a>
1. Domagoj Bradac, Matija Bucic, and Benny Sudakov, Turan numbers of sunflowers. <a href="https://github.com/ustc-comb/ustc-comb.github.io/blob/gh-pages/downloads/BBS.pdf">pdf</a>
1. Keith Frankston, Jeff Kahn, and Bhargav Narayanan, On regular 3-wise intersecting families. <a href="https://github.com/ustc-comb/ustc-comb.github.io/blob/gh-pages/downloads/FKN.pdf">pdf</a>
1. Marcelo Campos, A new proof of the efficient container lemma. Chapter 4 in <a href="https://github.com/ustc-comb/ustc-comb.github.io/blob/gh-pages/downloads/EPS.pdf">pdf</a>
1. Omar Alrabiah and Venkatesan Guruswami, Near-Tight Bounds for 3-Query Locally Correctable Binary Linear Codes via Rainbow Cycles. <a href="https://github.com/ustc-comb/ustc-comb.github.io/blob/gh-pages/downloads/AG.pdf">pdf</a>
1. Matija Bucic, Stefan Glock, and Benny Sudakov, The intersection spectrum of 3-chromatic intersecting hypergraphs. <a href="https://github.com/ustc-comb/ustc-comb.github.io/blob/gh-pages/downloads/BGS.pdf">pdf</a>
1. Peter Keevash, Jason Long, Bhargav Narayanan, and Alex Scott, A universal exponent for homeomorphs. <a href="https://github.com/ustc-comb/ustc-comb.github.io/blob/gh-pages/downloads/KLNS.pdf">pdf</a>
1. David Ellis, Maria-Romina Ivan, and Imre Leader, Turan densities for daisies and hypercubes. <a href="https://github.com/ustc-comb/ustc-comb.github.io/blob/gh-pages/downloads/EIL.pdf">pdf</a>
1. Benny Sudakov and Istvan Tomon, The Turan number of bipartite graphs with no $K_{t,t}$. <a href="https://github.com/ustc-comb/ustc-comb.github.io/blob/gh-pages/downloads/ST19.pdf">pdf</a>
1. Ernie Croot, Izabella Laba, and Olof Sisask, Arithmetic progressions in sumsets and $L_p$-almost-periodicity. <a href="https://github.com/ustc-comb/ustc-comb.github.io/blob/gh-pages/downloads/CLS.pdf">pdf</a>
1. Jacques Verstraëte, On The Number Of Sets Of Cycle Lengths. <a href="https://github.com/ustc-comb/ustc-comb.github.io/blob/gh-pages/downloads/Verstraete.pdf">pdf</a>


## Presentation schedule
{if  site.data.teaching.AddComb2024.Presentations}
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
- Bollobas set-pairs inequality
- Sunflowers and Kahn-Kalai conjecture
- Dependent random choice
- Sum-product problem

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
