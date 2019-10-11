---
layout: page
title: Projects
---

<div class="projects">
  {% for project in site.projects %}
  <div class="project">
    <h1 class="project-title">
      <a href="{{ project.url }}">
        {{ project.title }}
      </a>
    </h1>
    {{ project.excerpt }}
  </div>
  {% endfor %}
</div>
 

