---
layout: page
permalink: /publications/
title: Publications
description: Publications in reversed chronological order. 
years: [2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016, 2015, 2014, 2013, 2012, 2011]
nav: true
nav_order: 2
---

Color codes discriminate between <span style="color:#00369f">journal articles</span>, <span style="color:#a624a6">conference papers</span>, <span style="color:#9a852e">preprints</span> and <span style="color:#408e8f">book chapters</span>.
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
