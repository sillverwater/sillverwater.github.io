---
layout: page
title: "Brand Logo Mosaic Automation Program"
lang: en
permalink: /en/projects/mosaic/
alt_url: /projects/mosaic/
importance: 5
ptype: "Capstone Project"
img: assets/img/projects/mosaic.jpg
period: "2023.03 - 2023.10"
cats: ["Computer Vision"]
tags: ["Object Detection", "Data Augmentation"]
---

<p class="ey-sub" style="color:var(--global-text-color-light)">2023.03 - 2023.10</p>

<div class="ey-pills"><span class="ey-pill ey-pill-main">Computer Vision</span><span class="ey-pill">Object Detection</span><span class="ey-pill">Data Augmentation</span></div>

<p><img src="{{ '/assets/img/projects/mosaic.jpg' | relative_url }}" alt="Brand Logo Mosaic Automation Program" class="img-fluid rounded z-depth-1" style="width:100%"></p>

<div class="ey-section"><h2>Background</h2>
<ul>
  <li>Growing need to selectively mask specific brand logos as product placement (PPL) increases in broadcast video</li>
  <li>Mosaicking with editing tools requires frame-by-frame manual tracking and masking, which is slow, costly, and error-prone</li>
  <li>No public dataset for brand masking</li>
</ul>
</div>

<div class="ey-section"><h2>Process</h2>
<ul>
  <li>Built a 25,574-image dataset by compositing 5 brand logos (Adidas, Nike, Samsung, LG, Apple) onto public images such as ADE20K</li>
  <li>Developed a logo detection model by fine-tuning a pretrained YOLOv5 (batch size 32, 15,000 steps)</li>
  <li>Implemented a PyQt5 GUI and OpenCV mosaic/Gaussian blur pipeline (upload video → choose method → save result)</li>
</ul>
</div>

<div class="ey-section"><h2>Results</h2>
<ul>
  <li>mAP@0.5 of about 0.97 for 5-brand logo detection</li>
  <li>Automated logo detection, mosaicking, and saving in a single run</li>
  <li>GUI-based program usable by non-developers</li>
</ul>
</div>

<div class="ey-section"><h2>Contribution</h2>
<ul>
  <li>Team member - synthetic dataset construction, detection model training and validation, GUI implementation</li>
</ul>
</div>

<p style="margin-top:2rem"><a href="{{ '/en/projects/' | relative_url }}">← All projects</a></p>
