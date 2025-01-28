---
layout: page
permalink: /pub_conf_jp/
title: Conferences (Japanese)
description:
years: [2025, 2024, 2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016, 2014, 2013, 2012]
nav: false
nav_order: 2
---
<!-- _pages/publications.md -->
<div class="publications">

<h5>NOTE</h5>

<p>
  Here, we show publications on non-peer reviewed domestic (Japanese) conferences/symposia.<br>
  These publications are extended abstracts.
</p>

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
    {% bibliography -f conf_jp --template bib-jp -q @*[year={{y}}]* %}
    {% bibliography -f conf_jp_new --template bib-jp -q @*[year={{y}}]* %}
{% endfor %}

</div>
