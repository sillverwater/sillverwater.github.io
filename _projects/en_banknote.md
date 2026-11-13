---
layout: page
title: "Banknote Serial Number Recognition"
description: "CRNN (ResNet + BiLSTM) OCR · undergraduate research"
lang: en
permalink: /en/projects/banknote/
alt_url: /projects/banknote/
category: "Computer Vision"
importance: 1
img: assets/img/projects/banknote.jpg
period: "Oct 2023 – Dec 2023"
tags: ["OCR", "CRNN", "Text Recognition"]
---

<p class="ey-sub" style="color:var(--global-text-color-light)">Oct 2023 – Dec 2023 · Undergraduate research · CEIC 2023, first author</p>

<p><span class="ey-tag">OCR</span> <span class="ey-tag">CRNN</span> <span class="ey-tag">Text Recognition</span></p>

<p><img src="{{ '/assets/img/projects/banknote.jpg' | relative_url }}" alt="Banknote Serial Number Recognition" class="img-fluid rounded z-depth-1" style="width:100%"></p>

<div class="ey-section"><h2>Background</h2>
<ul>
  <li>No dataset existed for Russian ruble serial number recognition</li>
  <li>Needed an OCR model that reads serial numbers including Cyrillic characters</li>
</ul>
</div>

<div class="ey-section"><h2>Approach</h2>
<ul>
  <li>Built and labeled 12,998 serial-number images from 7 ruble denominations</li>
  <li>Applied Gaussian-noise augmentation</li>
  <li>Designed a CRNN (ResNet features + BiLSTM sequence model) trained with CTC loss</li>
</ul>
</div>

<div class="ey-section"><h2>Results</h2>
<ul>
  <li>99.15% overall accuracy (100% on digits)</li>
  <li>New dataset and recognition model for Cyrillic serial numbers</li>
  <li>Poster presentation at CEIC 2023</li>
</ul>
</div>

<div class="ey-section"><h2>My Role</h2>
<ul>
  <li>Led the full study — dataset, model, evaluation</li>
  <li>Paper writing and presentation</li>
</ul>
</div>

<p style="margin-top:2rem"><a href="{{ '/en/projects/' | relative_url }}">← All projects</a></p>
