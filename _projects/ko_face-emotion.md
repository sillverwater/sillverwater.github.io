---
layout: page
title: "차량용 얼굴 인식 및 감정 분석 서비스"
lang: ko
permalink: /projects/face-emotion/
alt_url: /en/projects/face-emotion/
importance: 2
ptype: "산학 연구과제"
img: assets/img/projects/face_emotion.jpg
period: "2024.09 - 2025.01"
cats: ["Computer Vision", "On-Device AI"]
tags: ["Object Detection", "Face Recognition", "Emotion Recognition"]
---

<p class="ey-sub" style="color:var(--global-text-color-light)">2024.09 - 2025.01</p>

<div class="ey-pills"><span class="ey-pill ey-pill-main">Computer Vision</span><span class="ey-pill ey-pill-main">On-Device AI</span><span class="ey-pill">Object Detection</span><span class="ey-pill">Face Recognition</span><span class="ey-pill">Emotion Recognition</span></div>

<p><img src="{{ '/assets/img/projects/face_emotion.jpg' | relative_url }}" alt="차량용 얼굴 인식 및 감정 분석 서비스" class="img-fluid rounded z-depth-1" style="width:100%"></p>

<div class="ey-section"><h2>연구 배경</h2>
<ul>
  <li>차량 탑승자 인식과 운전자 상태 모니터링을 위한 실시간 온디바이스 AI 서비스 필요</li>
  <li>여러 Vision AI 모델을 제한된 연산 환경에서 하나의 서비스로 안정적으로 연동하는 것이 핵심 과제</li>
</ul>
</div>

<div class="ey-section"><h2>진행 과정</h2>
<ul>
  <li>YOLOv5 기반 얼굴 탐지 및 HRNetV2 기반 Landmark 검출·정렬</li>
  <li>PCA·ArcFace를 활용한 사용자 식별, SVM·EmoNet을 활용한 감정 분류</li>
  <li>다중 AI 모델 통합 및 온디바이스 AI 카메라 CatchCam 환경 최적화·실시간 검증</li>
</ul>
</div>

<div class="ey-section"><h2>성과</h2>
<ul>
  <li>YOLOv5 얼굴 탐지 mAP50 0.99</li>
  <li>PCA 기반 사용자 식별 정확도 99%</li>
  <li>전체 모델 용량 약 40% 감소</li>
  <li>전체 파이프라인을 하나의 디바이스에 통합해 실시간 서비스 구현</li>
</ul>
</div>

<div class="ey-section"><h2>기여도</h2>
<ul>
  <li>프로젝트 팀장 - 일정 관리 및 의뢰기업 요구사항 조율</li>
  <li>얼굴 탐지 모델, PCA 기반 사용자 식별 알고리즘 개발</li>
  <li>파이프라인 통합 및 NPU 검증</li>
</ul>
</div>

<p style="margin-top:2rem"><a href="{{ '/projects/' | relative_url }}">← 프로젝트 목록</a></p>
