---
layout: page
title: Projects
nav_title: Projects
description: Research and development projects, grouped by topic
permalink: /en/projects/
lang: en
alt_url: /projects/
nav: true
nav_order: 3
display_categories: ["On-device AI", "Computer Vision", "Others"]
---

<div class="projects">
{% for category in page.display_categories %}
  {% assign cat_projects = site.projects | where: "lang", "en" | where: "category", category | sort: "importance" %}
  {% if cat_projects.size > 0 %}
  <h2 class="category">{{ category }}</h2>
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in cat_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
{% endfor %}
</div>
