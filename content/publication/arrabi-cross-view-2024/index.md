---
title: 'Cross-View Meets Diffusion: Aerial Image Synthesis with Geometry and Text
  Guidance'
authors:
- Ahmad Arrabi
- admin
- Waqas Sultan
- Chen Chen
- Safwan Wshah
date: '2024-08-01'
publishDate: '2024-08-13T21:41:03.491006Z'
publication_types:
- paper-conference
publication: '*2025 IEEE/CVF Winter Conference on Applications of Computer Vision
  (WACV)*'
# doi: 10.48550/arXiv.2408.04224
abstract: Aerial imagery analysis is critical for many research fields. However, obtaining
  frequent high-quality aerial images is not always accessible due to its high effort
  and cost requirements. One solution is to use the Ground-to-Aerial (G2A) technique
  to synthesize aerial images from easily collectible ground images. However, G2A
  is rarely studied, because of its challenges, including but not limited to, the
  drastic view changes, occlusion, and range of visibility. In this paper, we present
  a novel Geometric Preserving Ground-to-Aerial (G2A) image synthesis (GPG2A) model
  that can generate realistic aerial images from ground images. GPG2A consists of
  two stages. The first stage predicts the Bird's Eye View (BEV) segmentation (referred
  to as the BEV layout map) from the ground image. The second stage synthesizes the
  aerial image from the predicted BEV layout map and text descriptions of the ground
  image. To train our model, we present a new multi-modal cross-view dataset, namely
  VIGORv2 which is built upon VIGOR with newly collected aerial images, maps, and
  text descriptions. Our extensive experiments illustrate that GPG2A synthesizes better
  geometry-preserved aerial images than existing models. We also present two applications,
  data augmentation for cross-view geo-localization and sketch-based region search,
  to further verify the effectiveness of our GPG2A. The code and data will be publicly
  available.
tags:
- Cross-view Image Synthesis
- Image Synthesis
- Diffusion Model
- ControlNet
links:
- name: URL
  url: http://arxiv.org/abs/2408.04224
---
