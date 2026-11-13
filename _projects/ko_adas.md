---
layout: page
title: "첨단 운전자 보조 시스템(ADAS) 구현"
lang: ko
permalink: /projects/adas/
alt_url: /en/projects/adas/
importance: 5
ptype: "팀 프로젝트"
img: assets/img/projects/adas.jpg
github: https://github.com/sillverwater/ADAS_Project
period: "2022.03 - 2022.06"
cats: ["Computer Vision", "On-Device AI"]
tags: ["Advanced Driver Assistance Systems", "Object Detection"]
---

<p class="ey-sub" style="color:var(--global-text-color-light)">2022.03 - 2022.06</p>

<div class="ey-pills"><span class="ey-pill ey-pill-main">Computer Vision</span><span class="ey-pill ey-pill-main">On-Device AI</span><span class="ey-pill">Advanced Driver Assistance Systems</span><span class="ey-pill">Object Detection</span></div>

<p><img src="{{ '/assets/img/projects/adas.jpg' | relative_url }}" alt="첨단 운전자 보조 시스템(ADAS) 구현" class="img-fluid rounded z-depth-1" style="width:100%"></p>

<div class="ey-section"><h2>연구 배경</h2>
<ul>
  <li>별도 센서 없이 카메라 영상만으로 차선 및 차량을 인식하는 ADAS 구현</li>
  <li>Jetson Nano 환경에서 객체 탐지와 영상처리의 실시간 동작 필요</li>
</ul>
</div>

<div class="ey-section"><h2>진행 과정</h2>
<ul>
  <li>OpenCV 기반 차선 검출 및 차선 이탈 경고 알고리즘 구현</li>
  <li>YOLOv3-tiny 기반 차량 객체 탐지 및 전방 위험 경고 로직 개발</li>
  <li>Jetson Nano 환경에서 영상처리 및 객체 탐지 파이프라인 통합</li>
</ul>
</div>

<div class="ey-section"><h2>성과</h2>
<ul>
  <li>Jetson Nano 환경에서 객체 탐지 약 23 FPS 달성</li>
  <li>차선 이탈 경고(LDW) 및 전방 차량 위험 경고 기능 구현</li>
  <li>카메라 기반 ADAS 프로토타입 End-to-End 구현</li>
</ul>
</div>

<div class="ey-section"><h2>기여도</h2>
<ul>
  <li>차선 검출 및 차선 이탈 경고 알고리즘 구현</li>
  <li>C++/OpenCV 기반 ADAS 시스템 통합 및 Edge 환경 검증</li>
</ul>
</div>

<div class="ey-links"><a href="https://github.com/sillverwater/ADAS_Project">GitHub</a></div>

<p style="margin-top:2rem"><a href="{{ '/projects/' | relative_url }}">← 프로젝트 목록</a></p>
