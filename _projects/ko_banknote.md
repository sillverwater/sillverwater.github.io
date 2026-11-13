---
layout: page
title: "딥러닝 기반 지폐 일련번호 인식"
description: "ResNet + BiLSTM CRNN OCR · 학부연구생"
lang: ko
permalink: /projects/banknote/
alt_url: /en/projects/banknote/
category: "Computer Vision"
importance: 1
img: assets/img/projects/banknote.jpg
---

<p class="ey-sub" style="color:var(--global-text-color-light)">2023.10 – 2023.12 · 학부연구생 연구 · CEIC 2023 제1저자</p>

<p><span class="ey-tag">OCR</span> <span class="ey-tag">CRNN</span> <span class="ey-tag">Text Recognition</span></p>

<p><img src="{{ '/assets/img/projects/banknote.jpg' | relative_url }}" alt="딥러닝 기반 지폐 일련번호 인식" class="img-fluid rounded z-depth-1" style="width:100%"></p>

<div class="ey-section"><h2>연구 배경</h2>
<ul>
  <li>러시아 루블 지폐 일련번호 인식을 위한 데이터셋 부족</li>
  <li>키릴 문자를 포함한 일련번호를 정확히 인식하는 OCR 모델 필요</li>
</ul>
</div>

<div class="ey-section"><h2>진행 과정</h2>
<ul>
  <li>루블 지폐 7개 권종의 일련번호 이미지 12,998장 구축·라벨링</li>
  <li>Gaussian Noise 증강 적용</li>
  <li>ResNet 특징 추출 + BiLSTM 시퀀스 예측 CRNN 설계, CTC Loss 학습</li>
</ul>
</div>

<div class="ey-section"><h2>성과</h2>
<ul>
  <li>전체 일련번호 인식 정확도 99.15% (숫자 100%)</li>
  <li>키릴 문자 포함 일련번호 데이터셋 및 자동 인식 모델 제시</li>
  <li>국내 학술대회 CEIC 2023 Poster Session 발표</li>
</ul>
</div>

<div class="ey-section"><h2>기여도</h2>
<ul>
  <li>연구 전 과정 주도 — 데이터셋 구축, 모델 개발, 성능 검증</li>
  <li>논문 작성 및 학술대회 발표</li>
</ul>
</div>

<p style="margin-top:2rem"><a href="{{ '/projects/' | relative_url }}">← 프로젝트 목록</a></p>
