---
layout: page
title: Blog 
permalink: /blog/
---

<div class="blog">
  {% for blogpost in site.posts %}
  <div class="blogpost">
    <h2 class="blogpost-title">
      <a href="{{ blogpost.url }}">
        {{ blogpost.title }}
      </a>
    </h2>
    {{ blogpost.excerpt }}
  </div>
  {% endfor %}
</div>
 

