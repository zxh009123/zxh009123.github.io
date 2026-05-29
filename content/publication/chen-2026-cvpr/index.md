---
title: 'Turning Generators into Retrievers: Unlocking MLLMs for Natural Language-Guided
  Geo-Localization'
authors:
- Yuqi Chen
- Xiaohan Zhang
- Ahmad Arrabi
- Waqas Sultani
- Chen Chen
- Safwan Wshah
date: '2026-06-01'
publishDate: '2026-05-29T00:15:11.466585Z'
publication_types:
- paper-conference
publication: '*Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern
  Recognition (CVPR) Findings*'
abstract: Natural-language Guided Cross-view Geo-localization (NGCG) aims to retrieve geo-tagged satellite imagery using textual descriptions of ground scenes. While recent NGCG methods commonly rely on CLIP-style dual-encoder architectures, they often suffer from weak cross-modal generalization and require complex architectural designs. In contrast, Multimodal Large Language Models (MLLMs) offer powerful semantic reasoning capabilities but are not directly optimized for retrieval tasks. In this work, we present a simple yet effective framework to adapt MLLMs for NGCG via parameter-efficient finetuning. Our approach optimizes latent representations within the MLLM while preserving its pretrained multimodal knowledge, enabling strong cross-modal alignment without redesigning model architectures. Through systematic analysis of diverse variables, from model backbone to feature aggregation, we provide practical and generalizable insights for leveraging MLLMs in NGCG. Our method achieves SOTA on GeoText-1652 with a 12.2% improvement in Text-to-Image Recall@1 and secures top performance in 5 out of 12 subtasks on CVG-Text, all while surpassing baselines with far fewer trainable parameters. These results position MLLMs as a robust foundation for semantic cross-view retrieval and pave the way for MLLM-based NGCG to be adopted as a scalable, powerful alternative to traditional dual-encoder designs. Project page and code are available at https://yuqichen888.github.io/NGCG-MLLMs-web/.
tags:
- Cross-View Image Geo-localization
- Large Language Model
- Vision Language Model
links:
- name: Website
  url: https://yuqichen888.github.io/NGCG-MLLMs-web/

url_pdf: 'https://arxiv.org/pdf/2604.10721'
url_code: 'https://github.com/yuqichen888/NGCG-MLLMs'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---
