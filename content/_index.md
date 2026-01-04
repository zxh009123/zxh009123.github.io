---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  # - block: markdown
  #   content:
  #     title: '📚 My Research'
  #     subtitle: ''
  #     text: |-
  #       My current research interest lies at the border of computer vision and remote sensing (e.g. visual geo-localization and segmentation/detection in aerial images). I am also interested in image synthesis and 3D reconstruction.
        
  #       Please reach out to collaborate! 😃
  #   design:
  #     columns: '1'
  - block: markdown
    content:
      title: '📰 News'
      subtitle: ''
      text: |-
        <ul>
        <li><p>[2025.12] Our Tutorial <b>Beyond Vision: Multimodal Perspectives for Cross-View Geo-Localization</b> has been selected to <a href="https://wacv.thecvf.com/Conferences/2026/Dates">WACV 2026</a>. The Tutorial website will come soon. See you in Tucson!</p></li>
        <li><p>[2025.09] I recieved $1000 Google Cloud Research Credits. Thanks Google for supporting my research!</p></li>
        <li><p>[2025.07] My co-authored paper <a href="https://arxiv.org/abs/2507.04107">VICI</a> has been accepted to ACMMM 2025 Workshop UAVs in Multimedia. Please check the <a href="https://github.com/tavisshore/VICI/tree/main/src">project webpage</a> for more details.</p></li>
        <li><p>[2025.07] I will serve as a PC member in AAAI 2026.</p></li>
        <li><p>[2025.05] I will serve as a PC member in ECAI 2025.</p></li>
        <li><p>[2025.02] I will serve as a reviewer in ICCV 2025.</p></li>
        <li><p>[2024.12] My research has been selected in WACV 2025 Doctoral Consortium. Thanks WACV!</p></li>
        <li><p>[2024.11] I will serve as a reviewer in CVPR 2025.</p></li>
        <li><p>[2024.11] I will co-organize <b>Cross-view Geo-localization: Current Challenges and Future Frontiers with GenAI</b> tutorial in <a href="https://wacv2025.thecvf.com/">WACV 2025</a>. Refer to our <a href="https://zxh009123.github.io/WACV25_CVGL_Tutorial/">tutorial website</a> for more details. See you in Tucson!</p></li>
        <li><p>[2024.10] My co-authored paper <a href="https://arxiv.org/abs/2408.04224">GPG2A</a> has been accepted to WACV 2025. Please check the <a href="https://ahmadarrabi.github.io/GPG2A_web/">project webpage</a> for more details.</p></li>
        <li><p>[2024.9] My paper <a href="https://arxiv.org/abs/2308.09624">GeoDTR+</a> has been accepted by IEEE TPAMI. The code and weights have been open-sourced on the <a href="https://github.com/zxh009123/GeoDTR_plus">GitHub</a> page.</p></li>
        </ul>
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: 🌟 Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: 🚀 Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     view: article-grid
  #     columns: 1
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: date-title-summary
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
  - block: cta-card
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

        Easily build anything with blocks - no-code required!
        
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
