---
layout: page
title: "Camera-based ADAS"
description: "Lane departure & forward collision warning on Jetson Nano"
lang: en
permalink: /en/projects/adas/
alt_url: /projects/adas/
category: "Computer Vision"
importance: 2
img: assets/img/projects/adas.jpg
github: https://github.com/sillverwater/ADAS_Project
---

<p class="ey-sub" style="color:var(--global-text-color-light)">Mar 2022 – Jun 2022 · Course project</p>

<p><span class="ey-tag">ADAS</span> <span class="ey-tag">Object Detection</span> <span class="ey-tag">OpenCV</span> <span class="ey-tag">Jetson</span></p>

<p><img src="{{ '/assets/img/projects/adas.jpg' | relative_url }}" alt="Camera-based ADAS" class="img-fluid rounded z-depth-1" style="width:100%"></p>

<div class="ey-section"><h2>Background</h2>
<ul>
  <li>Build ADAS functions from a single camera, without extra sensors</li>
  <li>Run detection and image processing in real time on Jetson Nano</li>
</ul>
</div>

<div class="ey-section"><h2>Approach</h2>
<ul>
  <li>OpenCV lane detection (HSV, ROI, HoughLinesP) and lane-departure warning</li>
  <li>Vehicle detection with YOLOv3-tiny and forward-risk warning logic</li>
  <li>Integrated the pipeline on Jetson Nano</li>
</ul>
</div>

<div class="ey-section"><h2>Results</h2>
<ul>
  <li>~23 FPS object detection on Jetson Nano</li>
  <li>Lane departure warning (LDW) and forward vehicle warning</li>
  <li>End-to-end camera-based ADAS prototype</li>
</ul>
</div>

<div class="ey-section"><h2>My Role</h2>
<ul>
  <li>Lane detection and LDW algorithm</li>
  <li>C++/OpenCV system integration and edge validation</li>
</ul>
</div>

<p><a class="ey-btn" href="https://github.com/sillverwater/ADAS_Project">GitHub</a></p>

<p style="margin-top:2rem"><a href="{{ '/en/projects/' | relative_url }}">← All projects</a></p>
