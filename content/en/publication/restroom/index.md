---
title: 'Public Restroom Detection on Mobile Phone via Active Probing'
authors:
  - Mingming Fan
  - Alexander T. Adams
  - Khai N. Truong
author_notes:
  - 
  - 
  -
  -
  -
  -
date: '2014-02-11T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type: 
# 0 = Uncategorized; 1 = Accessibility & Aging; 2 = VR/AR/Metaverse; 3 = Human-AI Collaboration; 4 = UX Methodology; 5 = Social Computing; 6 = Sensing;  7 = Thesis; 8 = Patent
publication_types: ['6']

# Publication name and optional abbreviated publication name.
publication: In 2014 ACM International Symposium on Wearable Computers (ISWC'14)
publication_short: ISWC 2014

abstract: Although there are clear benefits to automatic image capture services by wearable devices, image capture sometimes happens in sensitive spaces where camera use is not appropriate. In this paper, we tackle this problem by focusing on detecting when the user of a wearable device is located in a specific type of private space---the public restroom---so that the image capture can be disabled. We present an infrastructure-independent method that uses just the microphone and the speaker on a commodity mobile phone. Our method actively probes the environment by playing a 0.1 seconds sine wave sweep sound and then analyzes the impulse response (IR) by extracting MFCCs features. These features are then used to train an SVM model. Our evaluation results show that we can train a general restroom model which is able to recognize new restrooms. We demonstrate that this approach works on different phone hardware. Furthermore, the volume levels, occupancy and presence of other sounds do not affect recognition in significant ways. We discuss three types of errors that the prediction model has and evaluate two proposed smoothing algorithms for improving recognition.

# Summary. An optional shortened abstract.
summary:

keywords: Restroom detection, room impulse response, active probing, pattern recognition

tags:
  - Restroom detection
  - room impulse response
  - active probing
  - pattern recognition
featured: false

links:
  # - name: Custom Link
  #   url: http://example.org
url_pdf: 'https://www.mingmingfan.com/papers/ISWC14-restroom-detection.pdf'
# url_code: 'https://github.com/tjusenchen/Xbot'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: 'https://sites.google.com/view/mobile-accessibility/'
url_video: 'https://www.youtube.com/watch?v=WLWRAHnDjec'

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

{{< youtube WLWRAHnDjec >}}


