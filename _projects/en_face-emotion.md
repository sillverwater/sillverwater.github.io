---
layout: page
title: "In-Vehicle Face Recognition and Emotion Analysis Service"
description: "02 | Industry Research Project (1)"
lang: en
permalink: /en/projects/face-emotion/
alt_url: /projects/face-emotion/
importance: 2
ptype: "Contract Research"
img: assets/img/projects/face_emotion.jpg
period: "2024.09 - 2025.01"
tags: ["Object Detection", "Face Recognition", "Emotion Recognition"]
---

<p class="ey-sub" style="color:var(--global-text-color-light)">2024.09 - 2025.01</p>

<div class="ey-pills"><span class="ey-pill">Object Detection</span><span class="ey-pill">Face Recognition</span><span class="ey-pill">Emotion Recognition</span></div>

<p><img src="{{ '/assets/img/projects/face_emotion.jpg' | relative_url }}" alt="In-Vehicle Face Recognition and Emotion Analysis Service" class="img-fluid rounded z-depth-1" style="width:100%"></p>

<div class="ey-section"><h2>Background</h2>
<ul>
  <li>Need for a real-time on-device AI service for occupant recognition and driver-state monitoring</li>
  <li>Key challenge: reliably integrating multiple Vision AI models into one service under limited compute</li>
</ul>
</div>

<div class="ey-section"><h2>Process</h2>
<ul>
  <li>YOLOv5-based face detection and HRNetV2-based landmark detection and alignment</li>
  <li>User identification with PCA and ArcFace, emotion classification with SVM and EmoNet</li>
  <li>Integrated multiple AI models, optimized and validated in real time on the CatchCam on-device AI camera</li>
</ul>
</div>

<div class="ey-section"><h2>Results</h2>
<ul>
  <li>YOLOv5 face detection mAP50 0.99</li>
  <li>99% user identification accuracy with PCA</li>
  <li>~40% smaller total model size</li>
  <li>Real-time service with the full pipeline integrated on a single device</li>
</ul>
</div>

<div class="ey-section"><h2>Contribution</h2>
<ul>
  <li>Project lead - schedule management and coordination of client requirements</li>
  <li>Developed the face detection model and PCA-based user identification algorithm</li>
  <li>Pipeline integration and NPU validation</li>
</ul>
</div>

<p style="margin-top:2rem"><a href="{{ '/en/projects/' | relative_url }}">← All projects</a></p>
