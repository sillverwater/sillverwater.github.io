---
layout: page
title: "Edge Device(NPU) 환경을 위한 실시간 홍채 인식 시스템"
description: "03 | 기업 연구과제 (2)"
lang: ko
permalink: /projects/iris/
alt_url: /en/projects/iris/
importance: 3
ptype: "연구 용역 과제"
img: assets/img/projects/iris.jpg
period: "2024.05 - 2024.08"
tags: ["Image Segmentation", "Iris Recognition"]
---

<p class="ey-sub" style="color:var(--global-text-color-light)">2024.05 - 2024.08</p>

<div class="ey-pills"><span class="ey-pill">Image Segmentation</span><span class="ey-pill">Iris Recognition</span></div>

<p><img src="{{ '/assets/img/projects/iris.jpg' | relative_url }}" alt="Edge Device(NPU) 환경을 위한 실시간 홍채 인식 시스템" class="img-fluid rounded z-depth-1" style="width:100%"></p>

<div class="ey-section"><h2>연구 배경</h2>
<ul>
  <li>홍채 인식 모델을 Edge Device에서 실시간으로 구동하기 위한 최적화 필요</li>
  <li>Segmentation과 Iris Code를 결합한 Hybrid 인식 시스템 개발</li>
</ul>
</div>

<div class="ey-section"><h2>진행 과정</h2>
<ul>
  <li>홍채·동공·눈꺼풀 영역 라벨링 및 YOLOv8s 기반 Segmentation 모델 개발</li>
  <li>속눈썹 제거, Iris Code 추출, Hamming Distance 기반 식별 구현</li>
  <li>Jetson Nano 및 Mythic NPU 환경에서 모델 최적화와 성능 검증</li>
</ul>
</div>

<div class="ey-section"><h2>성과</h2>
<ul>
  <li>Segmentation 모델 평균 IoU 0.96</li>
  <li>NPU에서 전체 시스템 평균 처리시간 47 ms (21 FPS)</li>
  <li>Edge Device에서도 높은 성능을 확보한 Hybrid 홍채 인식 시스템 구현</li>
  <li>국제 학술대회(ICGHIT 2025) Oral Session 발표</li>
</ul>
</div>

<div class="ey-section"><h2>기여도</h2>
<ul>
  <li>데이터셋 구축, 홍채 Segmentation 모델 개발, NPU 검증</li>
  <li>논문 작성 및 학술대회 발표</li>
</ul>
</div>

<p style="margin-top:2rem"><a href="{{ '/projects/' | relative_url }}">← 프로젝트 목록</a></p>
