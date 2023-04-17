---
layout: page
permalink: /pub_other_jp/
title: Others (Japanese)
description:
years: [2022, 2020, 2019, 2018, 2017]
nav: false
nav_order: 2
---

<h4>解説記事など</h4>

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f other_jp --template bib-jp -q @*[year={{y}}]* %}
{% endfor %}

</div>
