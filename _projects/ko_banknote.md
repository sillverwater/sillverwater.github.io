---
layout: page
title: "딥러닝 기반의 지폐 일련번호 인식 모델"
lang: ko
permalink: /projects/banknote/
alt_url: /en/projects/banknote/
importance: 4
ptype: "개인 연구"
img: assets/img/projects/banknote.jpg
period: "2023.10 - 2023.12"
cats: ["Computer Vision"]
tags: ["Optical Character Recognition", "Text Recognition"]
---

<p class="ey-sub" style="color:var(--global-text-color-light)">2023.10 - 2023.12</p>

<div class="ey-pills"><span class="ey-pill ey-pill-main">Computer Vision</span><span class="ey-pill">Optical Character Recognition</span><span class="ey-pill">Text Recognition</span></div>

<p><img src="{{ '/assets/img/projects/banknote.jpg' | relative_url }}" alt="딥러닝 기반의 지폐 일련번호 인식 모델" class="img-fluid rounded z-depth-1" style="width:100%"></p>

<div class="ey-section"><h2>연구 배경</h2>
<ul>
  <li>러시아 루블 지폐 일련번호 인식을 위한 데이터셋 부족</li>
  <li>키릴 문자를 포함한 일련번호를 정확히 인식하는 OCR 모델 개발 필요</li>
</ul>
</div>

<div class="ey-section"><h2>진행 과정</h2>
<ul>
  <li>러시아 루블 지폐 7개 권종의 일련번호 이미지 12,998장 라벨링</li>
  <li>가우시안 노이즈 증강 적용 및 학습 데이터셋 구축</li>
  <li>ResNet 기반 특징 추출과 BiLSTM 기반 시퀀스 예측을 결합한 CRNN 모델 설계</li>
</ul>
</div>

<div class="ey-section"><h2>성과</h2>
<ul>
  <li>전체 일련번호 인식 정확도 99%</li>
  <li>키릴 문자를 포함한 러시아 루블 지폐 일련번호 데이터셋 구축 및 자동 인식 모델 제시</li>
  <li>국내 학술대회(CEIC 2023) Poster Session 발표</li>
</ul>
</div>

<div class="ey-section"><h2>기여도</h2>
<ul>
  <li>연구 전 과정 주도 - 데이터셋 구축, 모델 개발, 성능 검증</li>
  <li>논문 작성 및 학술대회 발표</li>
</ul>
</div>

<div class="ey-section"><h2>관련 논문</h2>
<div class="ey-links"><a href="{{ '/publications/#pub-ceic-2023' | relative_url }}">CEIC 2023</a></div>
</div>

<p style="margin-top:2rem"><a href="{{ '/projects/' | relative_url }}">← 프로젝트 목록</a></p>
