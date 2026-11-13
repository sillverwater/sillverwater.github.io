---
layout: page
title: Projects
nav_title: Projects
description: 연구·개발 프로젝트
permalink: /projects/
lang: ko
alt_url: /en/projects/
nav: true
nav_order: 3
---

<div class="ey-plist">
{% assign ps = site.projects | where: "lang", "ko" | sort: "importance" %}{% for project in ps %}
<a class="ey-pcard" href="{{ project.url | relative_url }}">
  {% if project.img %}<div class="ey-pcard-img"><img src="{{ project.img | prepend: '/' | relative_url }}" alt="{{ project.title }}" loading="lazy"></div>{% endif %}
  <div class="ey-pcard-body">
    <div class="ey-pcard-cat">{{ project.ptype }}</div>
    <div class="ey-pcard-title">{{ project.title }}</div>
    <div class="ey-pcard-period">{{ project.period }}</div>
    <div class="ey-pills">{% for t in project.cats %}<span class="ey-pill ey-pill-main">{{ t }}</span>{% endfor %}{% for t in project.tags %}<span class="ey-pill">{{ t }}</span>{% endfor %}</div>
  </div>
</a>
{% endfor %}
</div>

