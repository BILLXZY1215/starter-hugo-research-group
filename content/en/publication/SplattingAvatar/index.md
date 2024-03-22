---
title: 'SplattingAvatar: Realistic Real-Time Human Avatars with Mesh-Embedded Gaussian Splatting'
authors:
  - Zhijing Shao
  - Zhaolong Wang
  - Zhuang Li
  - Duotun Wang
  - Xiangru Li 
  - Yu Zhang
  - Mingming Fan
  - Zeyu Wang
author_notes:
  - 
  - 
  -
  -
  -
  -
  -
  - corresponding author
date: '2024-03-22T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-03-22T00:00:00Z'

# Publication type: 
# 0 = Uncategorized; 1 = Accessibility & Aging; 2 = VR/AR/Metaverse; 3 = Human-AI Collaboration; 4 = UX Methodology; 5 = Social Computing; 6 = Sensing; 
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: Computer Vision and Pattern Recognition (CVPR)
publication_short: CVPR 2024

abstract: We present SplattingAvatar, a hybrid 3D representation of photorealistic human avatars with Gaussian Splatting embedded on a triangle mesh, which renders over 300 FPS on a modern GPU and 30 FPS on a mobile device. We disentangle the motion and appearance of a virtual human with explicit mesh geometry and implicit appearance modeling with Gaussian Splatting. The Gaussians are defined by barycentric coordinates and displacement on a triangle mesh as Phong surfaces. We extend lifted optimization to simultaneously optimize the parameters of the Gaussians while walking on the triangle mesh. SplattingAvatar is a hybrid representation of virtual humans where the mesh represents low-frequency motion and surface deformation, while the Gaussians take over the high-frequency geometry and detailed appearance. Unlike existing deformation methods that rely on an MLP-based linear blend skinning (LBS) field for motion, we control the rotation and translation of the Gaussians directly by mesh, which empowers its compatibility with various animation techniques, e.g., skeletal animation, blend shapes, and mesh editing. Trainable from monocular videos for both full-body and head avatars, SplattingAvatar shows state-of-the-art rendering quality across multiple datasets.

# Summary. An optional shortened abstract.
summary:

keywords: Content level measurement; container; active probing; impulse response

tags:
  - 
featured: false

links:
  # - name: Custom Link
  #   url: http://example.org
url_pdf: 'https://arxiv.org/abs/2403.05087'
# url_code: 'https://github.com/tjusenchen/Xbot'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: 'https://sites.google.com/view/mobile-accessibility/'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides:
---


