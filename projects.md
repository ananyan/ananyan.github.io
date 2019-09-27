---
layout: page
title: Projects
---

{% for projects in site.projects %}
  <h2>
    {{ projects.title }}
  </h2>
{% endfor %}