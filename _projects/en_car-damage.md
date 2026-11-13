---
layout: page
title: "Vehicle Damage Detection Project"
lang: en
permalink: /en/projects/car-damage/
alt_url: /projects/car-damage/
importance: 6
ptype: "Team Project"
period: "2022.09 - 2022.12"
cats: ["Computer Vision"]
tags: ["Image Segmentation", "U-Net"]
---

<p class="ey-sub" style="color:var(--global-text-color-light)">2022.09 - 2022.12</p>

<div class="ey-pills"><span class="ey-pill ey-pill-main">Computer Vision</span><span class="ey-pill">Image Segmentation</span><span class="ey-pill">U-Net</span></div>



<div class="ey-section"><h2>Background</h2>
<ul>
  <li>Visual inspection when returning rental cars is subjective and error-prone, leading to disputes</li>
  <li>Individual car owners struggle to assess damage quantitatively, creating information asymmetry in repair decisions</li>
  <li>Need for a service that consistently determines damage presence, type, and location from images and connects to repair shop search</li>
</ul>
</div>

<div class="ey-section"><h2>Process</h2>
<ul>
  <li>Collected the AI-Hub accident vehicle image dataset and preprocessed labels for segmentation training</li>
  <li>Developed a U-Net segmentation model for 4 damage types: Breakage, Crushed, Separated, Scratch</li>
  <li>Visualized damaged regions by overlaying predicted masks on the original image with OpenCV</li>
  <li>Built a Flask web service - rental car before/after comparison, personal car damage analysis, and region-based repair shop recommendation</li>
</ul>
</div>

<div class="ey-section"><h2>Results</h2>
<ul>
  <li>Implemented detection of 4 damage types and their regions</li>
  <li>Implemented damage comparison between rental car images before and after rental</li>
  <li>Completed an end-to-end web service: image upload, inference, visualization, and results</li>
</ul>
</div>

<div class="ey-section"><h2>Contribution</h2>
<ul>
  <li>Team lead - schedule and role management, scope coordination</li>
  <li>Dataset collection and preprocessing, U-Net segmentation model development</li>
  <li>Result visualization and Flask web service integration</li>
</ul>
</div>

<p style="margin-top:2rem"><a href="{{ '/en/projects/' | relative_url }}">← All projects</a></p>
