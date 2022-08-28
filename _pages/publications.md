---
layout: page
permalink: /publications/
title: publications
order: 1
description: "PDFs are accepted final manuscripts before copyediting, HTMLs are official published versions. Some of the analysis code associated with these publications can be found on my Github page: https://github.com/ananyan."
years: [2022, 2021, 2020, 2019]
nav: true
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
