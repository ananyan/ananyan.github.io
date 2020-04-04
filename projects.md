---
layout: page
title: Projects
permalink: /projects/
---

<div class="projects">
  {% for project in site.projects reversed %}
  <div class="project">
    <h2 class="project-title">
      <a href="{{ project.url }}">
        {{ project.title }}
      </a>
    </h2>
    {{ project.excerpt }}
  </div>
  {% endfor %}
</div>
 

