---
layout: page
permalink: /publications/
title: publications
order: 1
description: "I am interested in studying perception and decision making during complex, creative contexts, drawing from design theory and methodology (e.g., functional modeling, product semantics), cognitive science (e.g., analogy, similarity), and computer science (e.g., low-dimensional embeddings, preference learning, interactive interfaces). In the publications below, PDFs are accepted final manuscripts before copyediting, HTMLs are official published versions."
years: [2023, 2022, 2021, 2020, 2019]
nav: true
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
