---
layout: page
permalink: /publications/
title: publications
order: 1
description: "In the publications below, PDFs are accepted final manuscripts before copyediting, HTMLs are official published versions."
years: [2024, 2023, 2022, 2021, 2020, 2019]
nav: true
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
