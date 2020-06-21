---
layout: page
title: Projects
permalink: /projects/
---

<div class="content-box clearfix">
  {% for project in site.projects reversed %}
	<article class="project">
		{% if project.img %}
			<a class="project-thumbnail" style="background-image: url({{"/images/" | prepend: site.baseurl | append : project.img}})" href="{{project.url | prepend: site.baseurl}}"></a> 
		{% else %}
		{% endif %}
		<div class="project-content">
			<h2 class="project-title">
			  <a href="{{ project.url }}">
				{{ project.title }}
			  </a>
			</h2>
			<p class="project-skills">{{ project.skills }}</p>
		</div>
	</article>
  {% endfor %}
</div>