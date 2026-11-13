---
layout: page
title: "차량 파손 검출 프로젝트"
lang: ko
permalink: /projects/car-damage/
alt_url: /en/projects/car-damage/
importance: 6
ptype: "팀 프로젝트"
img: assets/img/projects/car_damage.jpg
period: "2022.09 - 2022.12"
cats: ["Computer Vision"]
tags: ["Image Segmentation", "U-Net"]
---

<p class="ey-sub" style="color:var(--global-text-color-light)">2022.09 - 2022.12</p>

<div class="ey-pills"><span class="ey-pill ey-pill-main">Computer Vision</span><span class="ey-pill">Image Segmentation</span><span class="ey-pill">U-Net</span></div>

<p><img src="{{ '/assets/img/projects/car_damage.jpg' | relative_url }}" alt="차량 파손 검출 프로젝트" class="img-fluid rounded z-depth-1" style="width:100%"></p>

<div class="ey-section"><h2>연구 배경</h2>
<ul>
  <li>렌터카 반납·정비 과정에서 육안 확인 방식은 주관적이고 누락이 발생해 분쟁 가능성 존재</li>
  <li>개인 사용자도 파손 부위를 정량적으로 파악하기 어려워 수리 의사결정에 정보 비대칭이 큼</li>
  <li>파손 여부·유형·위치를 이미지로 일관되게 판정하고 정비소 탐색까지 연결하는 서비스 필요</li>
</ul>
</div>

<div class="ey-section"><h2>진행 과정</h2>
<ul>
  <li>AI-Hub 사고 자동차 이미지 데이터셋 수집 및 Segmentation 학습용 라벨 전처리</li>
  <li>U-Net 기반 Breakage / Crushed / Separated / Scratch 4가지 파손 유형 Segmentation 모델 개발</li>
  <li>OpenCV로 예측 마스크를 원본 이미지 위에 오버레이해 파손 부위 시각화</li>
  <li>Flask 기반 웹 서비스 구축 - 렌터카 대여 전·후 비교, 개인 차량 파손 분석 및 지역 기반 정비소 추천</li>
</ul>
</div>

<div class="ey-section"><h2>성과</h2>
<ul>
  <li>4가지 파손 유형 및 영역 검출 기능 구현</li>
  <li>렌터카 대여 전·후 이미지 비교를 통한 파손 유무 판단 기능 구현</li>
  <li>이미지 업로드–추론–시각화–결과 제공의 End-to-End 웹 서비스 완성</li>
</ul>
</div>

<div class="ey-section"><h2>기여도</h2>
<ul>
  <li>팀장 - 일정·역할 분담 및 구현 범위 조율</li>
  <li>데이터셋 수집·전처리, U-Net Segmentation 모델 개발</li>
  <li>결과 시각화 및 Flask 웹 서비스 연동</li>
</ul>
</div>

<p style="margin-top:2rem"><a href="{{ '/projects/' | relative_url }}">← 프로젝트 목록</a></p>
