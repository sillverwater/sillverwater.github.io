---
layout: page
title: "상표 모자이크 자동화 프로그램"
lang: ko
permalink: /projects/mosaic/
alt_url: /en/projects/mosaic/
importance: 5
ptype: "학부 졸업 프로젝트"
img: assets/img/projects/mosaic.jpg
period: "2023.03 - 2023.10"
cats: ["Computer Vision"]
tags: ["Object Detection", "Data Augmentation"]
---

<p class="ey-sub" style="color:var(--global-text-color-light)">2023.03 - 2023.10</p>

<div class="ey-pills"><span class="ey-pill ey-pill-main">Computer Vision</span><span class="ey-pill">Object Detection</span><span class="ey-pill">Data Augmentation</span></div>

<p><img src="{{ '/assets/img/projects/mosaic.jpg' | relative_url }}" alt="상표 모자이크 자동화 프로그램" class="img-fluid rounded z-depth-1" style="width:100%"></p>

<div class="ey-section"><h2>연구 배경</h2>
<ul>
  <li>방송 영상 내 간접광고(PPL) 증가로 특정 브랜드 로고를 선택적으로 가려야 하는 요구 증가</li>
  <li>기존 편집툴 기반 모자이크는 프레임별 수작업 트래킹·마스킹이 필요해 시간·비용이 크고 오류가 잦음</li>
  <li>브랜드 마스킹을 위한 공개 데이터셋 부재</li>
</ul>
</div>

<div class="ey-section"><h2>진행 과정</h2>
<ul>
  <li>ADE20K 등 공개 이미지에 Adidas, Nike, Samsung, LG, Apple 5개 브랜드 로고를 합성해 25,574장 자체 데이터셋 구축</li>
  <li>YOLOv5 사전학습 모델 Fine-tuning으로 로고 탐지 모델 개발 (batch size 32, 15,000 steps)</li>
  <li>PyQt5 GUI와 OpenCV 기반 모자이크/가우시안 블러 처리 파이프라인 구현 (영상 업로드 → 방식 선택 → 결과 저장)</li>
</ul>
</div>

<div class="ey-section"><h2>성과</h2>
<ul>
  <li>5개 브랜드 로고 탐지 mAP@0.5 약 0.97</li>
  <li>로고 탐지–모자이크 처리–결과 저장을 한 번의 실행 흐름으로 자동화</li>
  <li>비개발자도 사용할 수 있는 GUI 기반 프로그램 구현</li>
</ul>
</div>

<div class="ey-section"><h2>기여도</h2>
<ul>
  <li>팀원 - 합성 기반 데이터셋 구축, 탐지 모델 학습·검증, GUI 프로그램 구현</li>
</ul>
</div>

<p style="margin-top:2rem"><a href="{{ '/projects/' | relative_url }}">← 프로젝트 목록</a></p>
