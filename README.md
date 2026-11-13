<div align="center">

# Eunsu Yun · Portfolio

**Computer Vision · On-device AI**

[![Website](https://img.shields.io/badge/Website-sillverwater.github.io-d94f7c?style=flat-square)](https://sillverwater.github.io)
[![English](https://img.shields.io/badge/English-/en/-555555?style=flat-square)](https://sillverwater.github.io/en/)
[![CV](https://img.shields.io/badge/CV-PDF-555555?style=flat-square)](https://sillverwater.github.io/assets/cv.pdf)

</div>

Source code for my personal academic portfolio. The site introduces my research on
**lightweight deep learning models that run in real time on edge devices** — from model design
to compression, quantization (FP16/INT8), and deployment on NPUs and NVIDIA Jetson.

엣지 디바이스에서 실시간으로 동작하는 경량 컴퓨터비전 모델 연구를 소개하는 개인 포트폴리오 사이트입니다.
한국어가 기본이며, 상단의 **KO | EN** 버튼으로 영어 페이지를 볼 수 있습니다.

## Contents

| Page | Description |
|---|---|
| **About** | Introduction, research interests, education, selected publication |
| **Publications** | SCIE journal article (*Sensors*, first author), M.S. thesis, conference papers |
| **Projects** | Research projects grouped by topic — On-device AI, Computer Vision, Others |
| **CV** | Education, research experience, industry projects, awards, certifications, skills |

### Featured projects

- **Lightweight Organoid Vasculature Classifier** — compressed EfficientNet on Jetson Nano and FuriosaAI Warboy NPU (~40% smaller, 31% lower latency) · *Sensors* 2026
- **Real-Time Iris Recognition on NPU** — YOLOv8s segmentation + iris code, 47 ms (21 FPS) on Mythic NPU · ICGHIT 2025
- **In-Vehicle Face & Emotion Recognition** — multi-model vision pipeline on a single edge device (team lead)
- **Banknote Serial Number Recognition** — CRNN (ResNet + BiLSTM) OCR, 99.15% accuracy · CEIC 2023
- **Camera-based ADAS** — lane departure and forward vehicle warning on Jetson Nano

## Structure

```
_pages/            Korean pages (default)
_pages/en/         English pages
_projects/         Project detail pages (ko_*.md, en_*.md)
_includes/         Navigation with KO/EN switch and theme colors
assets/cv.pdf      CV (PDF)
assets/img/        Project figures
```

## Built with

[Jekyll](https://jekyllrb.com/) and the [al-folio](https://github.com/alshedivat/al-folio) theme (MIT License).
Deployed automatically to GitHub Pages by GitHub Actions on every push to `main`.

## Contact

hkhk0331@gmail.com · [github.com/sillverwater](https://github.com/sillverwater)
