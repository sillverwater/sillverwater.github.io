---
layout: page
title: "Lightweight Organoid Vasculature Classifier"
description: "Compressed EfficientNet deployed on Jetson & NPU · M.S. thesis"
lang: en
permalink: /en/projects/organoid/
alt_url: /projects/organoid/
category: "On-device AI"
importance: 1
img: assets/img/projects/organoid.jpg
period: "Jun 2025 – Jan 2026"
tags: ["Image Classification", "Lightweight DL", "Quantization", "Jetson", "FuriosaAI"]
---

<p class="ey-sub" style="color:var(--global-text-color-light)">Jun 2025 – Jan 2026 · M.S. thesis · SCIE (Sensors), first author</p>

<p><span class="ey-tag">Image Classification</span> <span class="ey-tag">Lightweight DL</span> <span class="ey-tag">Quantization</span> <span class="ey-tag">Jetson</span> <span class="ey-tag">FuriosaAI</span></p>

<p><img src="{{ '/assets/img/projects/organoid.jpg' | relative_url }}" alt="Lightweight Organoid Vasculature Classifier" class="img-fluid rounded z-depth-1" style="width:100%"></p>

<div class="ey-section"><h2>Background</h2>
<ul>
  <li>Automate vasculature assessment of organoids, which relied on manual visual inspection</li>
  <li>Achieve both accuracy and real-time performance for deployment on edge devices</li>
</ul>
</div>

<div class="ey-section"><h2>Approach</h2>
<ul>
  <li>Built an organoid vasculature image dataset and mitigated class imbalance (augmentation, noise injection)</li>
  <li>Compressed EfficientNet — replaced SiLU with ReLU and removed SE blocks</li>
  <li>FP16 optimization on NVIDIA Jetson Nano, INT8 quantization and validation on FuriosaAI Warboy NPU</li>
</ul>
</div>

<div class="ey-section"><h2>Results</h2>
<ul>
  <li>~40% smaller model</li>
  <li>99% accuracy maintained on NPU with 31% lower inference latency</li>
  <li>Demonstrated automated vasculature assessment on-device</li>
  <li>Published as first author in <i>Sensors</i> (SCIE)</li>
</ul>
</div>

<div class="ey-section"><h2>My Role</h2>
<ul>
  <li>Led the entire study — dataset, model design & compression, NPU validation</li>
  <li>Wrote the paper</li>
</ul>
</div>

<p><a class="ey-btn" href="https://doi.org/10.3390/s26010112">DOI</a></p>

<p style="margin-top:2rem"><a href="{{ '/en/projects/' | relative_url }}">← All projects</a></p>
