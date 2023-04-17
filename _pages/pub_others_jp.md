---
layout: page
permalink: /pub_other_jp/
title: Others (Japanese)
description:
years: [2022, 2021, 2020, 2019, 2018, 2017]
nav: false
nav_order: 2
---
<!-- _pages/publications.md -->
<div class="publications">

<h4>解説記事・学会参加報告・etc.</h4>

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f other_jp --template bib-jp -q @*[year={{y}}]* %}
{% endfor %}

</div>


<!-- _pages/publications.md -->
<div class="publications">

<h4>特許</h4>

{% bibliography -f patent --template bib-jp %}

</div>


<!-- _pages/publications.md -->
<div class="publications">

<h4>競争的資金</h4>

<p>科研費研究者番号 : 60846690</p>

{% bibliography -f grant --template bib-jp %}

</div>
