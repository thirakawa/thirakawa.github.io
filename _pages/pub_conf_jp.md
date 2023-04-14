---
layout: page
permalink: /pub_conf_jp/
title: Conferences (Japanese)
description:
years: [2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016, 2015, 2014, 2013]
nav: false
nav_order: 2
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f conf_jp --template bib-jp -q @*[year={{y}}]* %}
{% endfor %}

</div>
