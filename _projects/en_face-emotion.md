---
layout: page
title: "In-Vehicle Face & Emotion Recognition"
description: "Multi-model vision pipeline on a single edge device · team lead"
lang: en
permalink: /en/projects/face-emotion/
alt_url: /projects/face-emotion/
category: "On-device AI"
importance: 3
img: assets/img/projects/face_emotion.jpg
---

<p class="ey-sub" style="color:var(--global-text-color-light)">Sep 2024 – Jan 2025 · Industry research project · DeepInsight</p>

<p><span class="ey-tag">Object Detection</span> <span class="ey-tag">Face Recognition</span> <span class="ey-tag">Emotion Recognition</span> <span class="ey-tag">On-device</span></p>

<p><img src="{{ '/assets/img/projects/face_emotion.jpg' | relative_url }}" alt="In-Vehicle Face & Emotion Recognition" class="img-fluid rounded z-depth-1" style="width:100%"></p>

<div class="ey-section"><h2>Background</h2>
<ul>
  <li>Real-time on-device AI for occupant identification and driver-state monitoring</li>
  <li>Key challenge: running several vision models reliably as one service on limited compute</li>
</ul>
</div>

<div class="ey-section"><h2>Approach</h2>
<ul>
  <li>Face detection with YOLOv5; landmark detection and alignment with HRNetV2</li>
  <li>User identification with ArcFace features + PCA; 7-class emotion recognition with EmoNet and SVM</li>
  <li>Integrated all models and optimized them for an on-device AI camera (CatchCam) with real-time validation</li>
</ul>
</div>

<div class="ey-section"><h2>Results</h2>
<ul>
  <li>Face detection mAP50 0.99</li>
  <li>99% user-identification accuracy (PCA)</li>
  <li>~40% smaller total model size</li>
  <li>Full pipeline running in real time on a single device</li>
</ul>
</div>

<div class="ey-section"><h2>My Role</h2>
<ul>
  <li>Team lead — schedule management and client requirements</li>
  <li>Developed face detection and PCA-based identification</li>
  <li>Pipeline integration and NPU validation</li>
</ul>
</div>

<p style="margin-top:2rem"><a href="{{ '/en/projects/' | relative_url }}">← All projects</a></p>
