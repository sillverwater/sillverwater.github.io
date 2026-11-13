---
layout: page
title: "Real-Time Iris Recognition on NPU"
description: "Hybrid segmentation + iris-code recognition · industry project"
lang: en
permalink: /en/projects/iris/
alt_url: /projects/iris/
category: "On-device AI"
importance: 2
img: assets/img/projects/iris.jpg
---

<p class="ey-sub" style="color:var(--global-text-color-light)">May 2024 – Aug 2024 · Industry research project · Hyundai MIB International</p>

<p><span class="ey-tag">Segmentation</span> <span class="ey-tag">YOLOv8</span> <span class="ey-tag">Iris Recognition</span> <span class="ey-tag">Mythic NPU</span> <span class="ey-tag">Jetson</span></p>

<p><img src="{{ '/assets/img/projects/iris.jpg' | relative_url }}" alt="Real-Time Iris Recognition on NPU" class="img-fluid rounded z-depth-1" style="width:100%"></p>

<div class="ey-section"><h2>Background</h2>
<ul>
  <li>Optimize iris recognition to run in real time on edge devices</li>
  <li>Build a hybrid system combining segmentation with iris codes</li>
</ul>
</div>

<div class="ey-section"><h2>Approach</h2>
<ul>
  <li>Labeled iris, pupil, and eyelid regions and trained a YOLOv8s segmentation model</li>
  <li>Implemented eyelash removal, iris-code extraction, and Hamming-distance matching</li>
  <li>Converted, optimized, and benchmarked models on Jetson Nano and Mythic NPU</li>
  <li>Collaborated in English with an overseas technical team to resolve NPU conversion issues</li>
</ul>
</div>

<div class="ey-section"><h2>Results</h2>
<ul>
  <li>Mean segmentation IoU 0.96</li>
  <li>47 ms average end-to-end latency on NPU (21 FPS)</li>
  <li>Oral presentation at ICGHIT 2025; first-author paper at IEIE Summer Conference 2025</li>
</ul>
</div>

<div class="ey-section"><h2>My Role</h2>
<ul>
  <li>Dataset construction, iris segmentation model, NPU validation</li>
  <li>Paper writing and conference presentation</li>
</ul>
</div>

<p style="margin-top:2rem"><a href="{{ '/en/projects/' | relative_url }}">← All projects</a></p>
