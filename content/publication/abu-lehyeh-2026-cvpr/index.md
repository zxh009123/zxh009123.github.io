---
title: 'GeoFlow: Real-Time Fine-Grained Cross-View Geolocalization via Iterative Flow
  Prediction'
authors:
- Ayesh Abu Lehyeh
- admin
- Ahmad Arrabi
- Waqas Sultani
- Chen Chen
- Safwan Wshah
date: '2026-06-01'
publishDate: '2026-05-28T22:45:40.173432Z'
publication_types:
- paper-conference
publication: '*Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern
  Recognition (CVPR)*'
abstract: Accurate and fast localization is vital for safe autonomous navigation in GPS-denied areas. Fine-Grained Cross-View Geolocalization (FG-CVG) aims to estimate the precise 2-Degree-of-Freedom (2-DoF) location of a ground image relative to a satellite image. However, current methods force a difficult trade-off, with high-accuracy models being slow for real-time use. In this paper, we introduce GeoFlow, a new approach that offers a lightweight and highly efficient framework that breaks this accuracy-speed trade-off. Our technique learns a direct probabilistic mapping, predicting the displacement (in distance and direction) required to correct any given location hypothesis. This is complemented by our novel inference algorithm, Iterative Refinement Sampling (IRS). Instead of trusting a single prediction, IRS refines a population of hypotheses, allowing them to iteratively ‘flow’ from random starting points to a robust, converged consensus. Even its iterative nature, this approach offers flexible inference-time scaling, allowing a direct trade-off between performance and computation without any re-training. Experiments on the KITTI and VIGOR datasets show that GeoFlow achieves state-of-the-art efficiency, running at real-time speeds of 29 FPS while maintaining competitive localization accuracy. This work opens a new path for the development of practical real-time geolocalization systems.
tags:
- Cross-view Image Synthesis
- Image Synthesis
- Diffusion Model
- ControlNet
links:
- name: Website
  url: https://ayeshabulehyeh.github.io/geoflow_page/

url_pdf: 'https://arxiv.org/pdf/2603.21943'
url_code: 'https://github.com/AyeshAbuLehyeh/GeoFlow'
url_dataset: ''
url_poster: ''
url_slides: ''
url_source: ''
url_video: ''
---
