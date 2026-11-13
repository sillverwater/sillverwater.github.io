---
layout: page
title: "오가노이드 이미지 기반 정상 및 비정상 혈관구조 분류를 위한 경량 딥러닝 모델"
lang: ko
permalink: /projects/organoid/
alt_url: /en/projects/organoid/
importance: 1
ptype: "학위 연구"
img: assets/img/projects/organoid.jpg
period: "2025.06 - 2026.01"
cats: ["Computer Vision", "On-Device AI"]
tags: ["Image Classification", "Lightweight Deep Learning"]
---

<p class="ey-sub" style="color:var(--global-text-color-light)">2025.06 - 2026.01</p>

<div class="ey-pills"><span class="ey-pill ey-pill-main">Computer Vision</span><span class="ey-pill ey-pill-main">On-Device AI</span><span class="ey-pill">Image Classification</span><span class="ey-pill">Lightweight Deep Learning</span></div>

<p><img src="{{ '/assets/img/projects/organoid.jpg' | relative_url }}" alt="오가노이드 이미지 기반 정상 및 비정상 혈관구조 분류를 위한 경량 딥러닝 모델" class="img-fluid rounded z-depth-1" style="width:100%"></p>

<div class="ey-section"><h2>연구 배경</h2>
<ul>
  <li>육안 판독 중심의 혈관구조 평가를 AI로 자동화</li>
  <li>Edge Device 적용을 위해 정확도와 실시간성 동시 확보 필요</li>
</ul>
</div>

<div class="ey-section"><h2>진행 과정</h2>
<ul>
  <li>오가노이드 혈관 이미지 데이터셋 구축 및 클래스 불균형 보완</li>
  <li>EfficientNet 기반 구조 경량화 및 정상·비정상 분류 모델 개발</li>
  <li>NVIDIA Jetson Nano: FP16 최적화, FuriosaAI Warboy NPU: INT8 양자화, 성능 검증</li>
</ul>
</div>

<div class="ey-section"><h2>성과</h2>
<ul>
  <li>모델 크기 40% 감소</li>
  <li>NPU에서 정확도 99% 유지, 추론 지연시간 31% 단축</li>
  <li>혈관구조 평가 자동화 및 온디바이스 적용 가능성 제시</li>
  <li>해외 SCIE 학술지(Sensors) 제1저자 게재</li>
</ul>
</div>

<div class="ey-section"><h2>기여도</h2>
<ul>
  <li>연구 전 과정 주도 - 데이터셋 구축, 모델 설계 및 경량화, NPU 검증</li>
  <li>논문 작성</li>
</ul>
</div>

<div class="ey-section"><h2>관련 논문</h2>
<div class="ey-links"><a href="{{ '/publications/#pub-ms' | relative_url }}">석사학위논문</a> <span class="ey-sep">·</span> <a href="{{ '/publications/#pub-sensors' | relative_url }}">Sensors 2026</a></div>
</div>

<p style="margin-top:2rem"><a href="{{ '/projects/' | relative_url }}">← 프로젝트 목록</a></p>
