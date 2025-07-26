---
title: 'VICI: VLM-Instructed Cross-view Image-localisation'
authors:
- admin
- Tavis Shore
- Chen Chen
- Oscar Mendez
- Simon Hadfield
- Safwan Wshah
date: '2025-07-21'
publishDate: '2025-07-13T21:41:03.437790Z'
publication_types:
- article-journal
publication: ''

abstract: In this paper, we present a high-performing solution to the UAVM 2025 Challenge, which focuses on matching narrow FOV street-level images to corresponding satellite imagery using the University-1652 dataset. As panoramic Cross-View Geo-Localisation nears peak performance, it becomes increasingly important to explore more practical problem formulations. Real-world scenarios rarely offer panoramic street-level queries; instead, queries typically consist of limited-FOV images captured with unknown camera parameters. Our work prioritises discovering the highest achievable performance under these constraints, pushing the limits of existing architectures. Our method begins by retrieving candidate satellite image embeddings for a given query, followed by a re-ranking stage that selectively enhances retrieval accuracy within the top candidates. This two-stage approach enables more precise matching, even under the significant viewpoint and scale variations inherent in the task. Through experimentation, we demonstrate that our approach achieves competitive results -specifically attaining R@1 and R@10 retrieval rates of 30.21% and 63.13% respectively. This underscores the potential of optimised retrieval and re-ranking strategies in advancing practical geo-localisation performance.
tags:
- Cross-View Image Geo-localization
- Large Vision-Language Model
links:
- name: URL
  url: https://arxiv.org/pdf/2507.04107

url_pdf: 'https://arxiv.org/pdf/2507.04107'
url_code: 'https://github.com/tavisshore/VICI'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---