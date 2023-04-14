---
layout: page
permalink: /pub_journal_en/
title: Journals (English)
description:
years: [2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016, 2013]
nav: false
nav_order: 2
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f journal_en -q @*[year={{y}}]* %}
{% endfor %}

</div>
