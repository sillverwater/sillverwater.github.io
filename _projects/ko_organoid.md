---
layout: page
title: "오가노이드 혈관구조 분류 경량 모델"
description: "EfficientNet 경량화 + Jetson·NPU 배포 · 석사 학위논문"
lang: ko
permalink: /projects/organoid/
alt_url: /en/projects/organoid/
category: "On-device AI"
importance: 1
img: assets/img/projects/organoid.jpg
---

<p class="ey-sub" style="color:var(--global-text-color-light)">2025.06 – 2026.01 · 석사 학위논문 · SCIE (Sensors) 제1저자</p>

<p><span class="ey-tag">Image Classification</span> <span class="ey-tag">Lightweight DL</span> <span class="ey-tag">Quantization</span> <span class="ey-tag">Jetson</span> <span class="ey-tag">FuriosaAI</span></p>

<p><img src="{{ '/assets/img/projects/organoid.jpg' | relative_url }}" alt="오가노이드 혈관구조 분류 경량 모델" class="img-fluid rounded z-depth-1" style="width:100%"></p>

<div class="ey-section"><h2>연구 배경</h2>
<ul>
  <li>육안 판독에 의존하던 오가노이드 혈관구조 평가를 AI로 자동화</li>
  <li>Edge Device 적용을 위해 정확도와 실시간성을 동시에 확보해야 함</li>
</ul>
</div>

<div class="ey-section"><h2>진행 과정</h2>
<ul>
  <li>오가노이드 혈관 이미지 데이터셋 구축 및 클래스 불균형 보완 (증강·노이즈 추가)</li>
  <li>EfficientNet 기반 구조 경량화 — SiLU→ReLU 교체, SE Block 제거</li>
  <li>NVIDIA Jetson Nano FP16 최적화, FuriosaAI Warboy NPU INT8 양자화 및 성능 검증</li>
</ul>
</div>

<div class="ey-section"><h2>성과</h2>
<ul>
  <li>모델 크기 약 40% 감소</li>
  <li>NPU에서 정확도 99% 유지, 추론 지연시간 31% 단축</li>
  <li>혈관구조 평가 자동화 및 온디바이스 적용 가능성 제시</li>
  <li>SCIE 학술지 <i>Sensors</i> 제1저자 게재</li>
</ul>
</div>

<div class="ey-section"><h2>기여도</h2>
<ul>
  <li>연구 전 과정 주도 — 데이터셋 구축, 모델 설계·경량화, NPU 검증</li>
  <li>논문 작성</li>
</ul>
</div>

<p><a class="ey-btn" href="https://doi.org/10.3390/s26010112">DOI</a></p>

<p style="margin-top:2rem"><a href="{{ '/projects/' | relative_url }}">← 프로젝트 목록</a></p>
