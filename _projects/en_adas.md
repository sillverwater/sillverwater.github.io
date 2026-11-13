---
layout: page
title: "Advanced Driver Assistance System (ADAS) Implementation"
lang: en
permalink: /en/projects/adas/
alt_url: /projects/adas/
importance: 7
ptype: "Team Project"
img: assets/img/projects/adas.jpg
github: https://github.com/sillverwater/ADAS_Project
period: "2022.03 - 2022.06"
cats: ["Computer Vision", "On-Device AI"]
tags: ["Advanced Driver Assistance Systems", "Object Detection"]
---

<p class="ey-sub" style="color:var(--global-text-color-light)">2022.03 - 2022.06</p>

<div class="ey-pills"><span class="ey-pill ey-pill-main">Computer Vision</span><span class="ey-pill ey-pill-main">On-Device AI</span><span class="ey-pill">Advanced Driver Assistance Systems</span><span class="ey-pill">Object Detection</span></div>

<p><img src="{{ '/assets/img/projects/adas.jpg' | relative_url }}" alt="Advanced Driver Assistance System (ADAS) Implementation" class="img-fluid rounded z-depth-1" style="width:100%"></p>

<div class="ey-section"><h2>Background</h2>
<ul>
  <li>Implementing ADAS that recognizes lanes and vehicles from camera images only, without extra sensors</li>
  <li>Real-time object detection and image processing needed on Jetson Nano</li>
</ul>
</div>

<div class="ey-section"><h2>Process</h2>
<ul>
  <li>Implemented OpenCV-based lane detection and lane departure warning algorithm</li>
  <li>Developed YOLOv3-tiny-based vehicle detection and forward collision warning logic</li>
  <li>Integrated the image processing and object detection pipeline on Jetson Nano</li>
</ul>
</div>

<div class="ey-section"><h2>Results</h2>
<ul>
  <li>Achieved ~23 FPS object detection on Jetson Nano</li>
  <li>Implemented lane departure warning (LDW) and forward vehicle warning</li>
  <li>End-to-end camera-based ADAS prototype</li>
</ul>
</div>

<div class="ey-section"><h2>Contribution</h2>
<ul>
  <li>Implemented lane detection and lane departure warning algorithm</li>
  <li>C++/OpenCV-based ADAS system integration and Edge validation</li>
</ul>
</div>

<div class="ey-links"><a href="https://github.com/sillverwater/ADAS_Project">GitHub</a></div>

<p style="margin-top:2rem"><a href="{{ '/en/projects/' | relative_url }}">← All projects</a></p>
