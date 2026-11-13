---
layout: page
title: "Real-Time Iris Recognition System for Edge Device (NPU) Environments"
lang: en
permalink: /en/projects/iris/
alt_url: /projects/iris/
importance: 3
ptype: "Industry Collaboration"
img: assets/img/projects/iris.jpg
period: "2024.05 - 2024.08"
cats: ["Computer Vision", "On-Device AI"]
tags: ["Image Segmentation", "Iris Recognition"]
---

<p class="ey-sub" style="color:var(--global-text-color-light)">2024.05 - 2024.08</p>

<div class="ey-pills"><span class="ey-pill ey-pill-main">Computer Vision</span><span class="ey-pill ey-pill-main">On-Device AI</span><span class="ey-pill">Image Segmentation</span><span class="ey-pill">Iris Recognition</span></div>

<p><img src="{{ '/assets/img/projects/iris.jpg' | relative_url }}" alt="Real-Time Iris Recognition System for Edge Device (NPU) Environments" class="img-fluid rounded z-depth-1" style="width:100%"></p>

<div class="ey-section"><h2>Background</h2>
<ul>
  <li>Optimization needed to run iris recognition models in real time on Edge Devices</li>
  <li>Developing a hybrid recognition system combining segmentation and Iris Code</li>
</ul>
</div>

<div class="ey-section"><h2>Process</h2>
<ul>
  <li>Labeled iris, pupil, and eyelid regions and developed a YOLOv8s-based segmentation model</li>
  <li>Implemented eyelash removal, Iris Code extraction, and Hamming Distance-based identification</li>
  <li>Model optimization and performance validation on Jetson Nano and Mythic NPU</li>
</ul>
</div>

<div class="ey-section"><h2>Results</h2>
<ul>
  <li>Mean IoU 0.96 for the segmentation model</li>
  <li>Average end-to-end processing time of 47 ms (21 FPS) on NPU</li>
  <li>Implemented a hybrid iris recognition system with high performance on Edge Devices</li>
  <li>Oral Session presentation at an international conference (ICGHIT 2025)</li>
</ul>
</div>

<div class="ey-section"><h2>Contribution</h2>
<ul>
  <li>Dataset construction, iris segmentation model development, NPU validation</li>
  <li>Paper writing and conference presentation</li>
</ul>
</div>

<div class="ey-section"><h2>Related Publications</h2>
<div class="ey-links"><a href="{{ '/en/publications/#pub-ieie-2025' | relative_url }}">IEIE 2025</a> <span class="ey-sep">·</span> <a href="{{ '/en/publications/#pub-icghit-2025' | relative_url }}">ICGHIT 2025</a></div>
</div>

<p style="margin-top:2rem"><a href="{{ '/en/projects/' | relative_url }}">← All projects</a></p>
