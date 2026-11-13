---
layout: page
title: "카메라 기반 ADAS 구현"
description: "차선 이탈·전방 차량 경고 · Jetson Nano"
lang: ko
permalink: /projects/adas/
alt_url: /en/projects/adas/
category: "Computer Vision"
importance: 2
img: assets/img/projects/adas.jpg
github: https://github.com/sillverwater/ADAS_Project
---

<p class="ey-sub" style="color:var(--global-text-color-light)">2022.03 – 2022.06 · 교내 프로젝트 (융합전자공학특강)</p>

<p><span class="ey-tag">ADAS</span> <span class="ey-tag">Object Detection</span> <span class="ey-tag">OpenCV</span> <span class="ey-tag">Jetson</span></p>

<p><img src="{{ '/assets/img/projects/adas.jpg' | relative_url }}" alt="카메라 기반 ADAS 구현" class="img-fluid rounded z-depth-1" style="width:100%"></p>

<div class="ey-section"><h2>연구 배경</h2>
<ul>
  <li>별도 센서 없이 카메라 영상만으로 차선과 차량을 인식하는 ADAS 구현</li>
  <li>Jetson Nano 환경에서 객체 탐지와 영상처리를 실시간으로 동작시켜야 함</li>
</ul>
</div>

<div class="ey-section"><h2>진행 과정</h2>
<ul>
  <li>OpenCV 기반 차선 검출(HSV 변환, ROI, HoughLinesP) 및 차선 이탈 경고 알고리즘 구현</li>
  <li>YOLOv3-tiny 기반 차량 탐지 및 전방 위험 경고 로직 개발</li>
  <li>Jetson Nano에서 영상처리·객체 탐지 파이프라인 통합</li>
</ul>
</div>

<div class="ey-section"><h2>성과</h2>
<ul>
  <li>Jetson Nano에서 객체 탐지 약 23 FPS</li>
  <li>차선 이탈 경고(LDW) 및 전방 차량 위험 경고 기능 구현</li>
  <li>카메라 기반 ADAS 프로토타입 End-to-End 구현</li>
</ul>
</div>

<div class="ey-section"><h2>기여도</h2>
<ul>
  <li>차선 검출 및 차선 이탈 경고 알고리즘 구현</li>
  <li>C++/OpenCV 기반 시스템 통합 및 Edge 환경 검증</li>
</ul>
</div>

<p><a class="ey-btn" href="https://github.com/sillverwater/ADAS_Project">GitHub</a></p>

<p style="margin-top:2rem"><a href="{{ '/projects/' | relative_url }}">← 프로젝트 목록</a></p>
