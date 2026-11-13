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
---

<div class="ey-tabs" role="tablist">
  <button class="ey-tab active" data-filter="all">All</button>
  <button class="ey-tab" data-filter="on-device-ai">On-device AI</button>
  <button class="ey-tab" data-filter="computer-vision">Computer Vision</button>
  <button class="ey-tab" data-filter="others">Others</button>
</div>

<div class="ey-plist">
{% assign cats = "On-device AI|Computer Vision|Others" | split: "|" %}
{% for c in cats %}{% assign ps = site.projects | where: "lang", "en" | where: "category", c | sort: "importance" %}{% for project in ps %}
<a class="ey-pcard" data-cat="{{ project.category | slugify }}" href="{{ project.url | relative_url }}">
  {% if project.img %}<div class="ey-pcard-img"><img src="{{ project.img | prepend: '/' | relative_url }}" alt="{{ project.title }}" loading="lazy"></div>{% endif %}
  <div class="ey-pcard-body">
    <div class="ey-pcard-cat">{{ project.category }}</div>
    <div class="ey-pcard-title">{{ project.title }}</div>
    <div class="ey-pcard-desc">{{ project.description }}</div>
    <div class="ey-pcard-period">{{ project.period }}</div>
    <div class="ey-pills">{% for t in project.tags %}<span class="ey-pill">{{ t }}</span>{% endfor %}</div>
  </div>
</a>
{% endfor %}{% endfor %}
</div>

<script>
  (function () {
    var tabs = document.querySelectorAll(".ey-tab");
    var cards = document.querySelectorAll(".ey-pcard");
    function apply(f) {
      tabs.forEach(function (t) { t.classList.toggle("active", t.getAttribute("data-filter") === f); });
      cards.forEach(function (c) { c.style.display = f === "all" || c.getAttribute("data-cat") === f ? "" : "none"; });
    }
    tabs.forEach(function (t) { t.addEventListener("click", function () { apply(t.getAttribute("data-filter")); history.replaceState(null, "", "#" + t.getAttribute("data-filter")); }); });
    var h = location.hash.replace("#", "");
    if (h && document.querySelector('.ey-tab[data-filter="' + h + '"]')) apply(h);
  })();
</script>
