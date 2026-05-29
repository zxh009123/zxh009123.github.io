---
title: 'Geo2: Geometry-Guided Cross-view Geo-Localization and Image Synthesis'
authors:
- Yancheng Zhang
- admin
- Guangyu Sun
- Zonglin Lyu
- Safwan Wshah
- Chen Chen
date: '2026-06-01'
publishDate: '2026-05-29T00:15:11.457436Z'
publication_types:
- paper-conference
publication: '*Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern
  Recognition (CVPR)*'
abstract: Cross-view geo-spatial learning consists of two important tasks':' Cross-View Geo-Localization (CVGL) and Cross-View Image Synthesis (CVIS), both of which rely on establishing geometric correspondences between ground and aerial views. Recent Geometric Foundation Models (GFMs) have demonstrated strong capabilities in extracting generalizable 3D geometric features from images, but their potential in cross-view geo-spatial tasks remains underexplored. In this work, we present Geo^2, a unified framework that leverages Geometric priors from GFMs (e.g., VGGT) to jointly perform geo-spatial tasks, CVGL and bidirectional CVIS. Despite the 3D reconstruction ability of GFMs, directly applying them to CVGL and CVIS remains challenging due to the large viewpoint gap between ground and aerial imagery. We propose GeoMap, which embeds ground and aerial features into a shared 3D-aware latent space, effectively reducing cross-view discrepancies for localization. This shared latent space naturally bridges cross-view image synthesis in both directions. To exploit this, we propose GeoFlow, a flow-matching model conditioned on geometry-aware latent embeddings. We further introduce a consistency loss to enforce latent alignment between the two synthesis directions, ensuring bidirectional coherence. Extensive experiments on standard benchmarks, including CVUSA, CVACT, and VIGOR, demonstrate that Geo^2 achieves state-of-the-art performance in both localization and synthesis, highlighting the effectiveness of 3D geometric priors for cross-view geo-spatial learning.
tags:
- Cross-view Image Geo-localization
- Cross-view Image Synthesis
- Flow Matching
- Diffusion
- 3D Foundation Model
links:
- name: Website
  url: https://fobow.github.io/geo2.github.io/

url_pdf: 'https://arxiv.org/pdf/2603.25819'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---
