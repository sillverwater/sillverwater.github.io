---
layout: page
title: Projects
nav_title: Projects
description: Research and development projects
permalink: /en/projects/
lang: en
alt_url: /projects/
nav: true
nav_order: 3
---

<div class="ey-plist">
{% assign cats = "On-device AI|Computer Vision" | split: "|" %}
{% for c in cats %}{% assign ps = site.projects | where: "lang", "en" | where: "category", c | sort: "importance" %}{% for project in ps %}
<a class="ey-pcard" data-cat="{{ project.category | slugify }}" href="{{ project.url | relative_url }}">
  {% if project.img %}<div class="ey-pcard-img"><img src="{{ project.img | prepend: '/' | relative_url }}" alt="{{ project.title }}" loading="lazy"></div>{% endif %}
  <div class="ey-pcard-body">
    <div class="ey-pcard-title">{{ project.title }}</div>
    <div class="ey-pcard-desc">{{ project.description }}</div>
    <div class="ey-pcard-period">{{ project.period }}</div>
    <div class="ey-pills">{% for t in project.tags %}<span class="ey-pill">{{ t }}</span>{% endfor %}</div>
  </div>
</a>
{% endfor %}{% endfor %}
</div>

