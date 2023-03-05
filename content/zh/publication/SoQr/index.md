---
title: 'SoQr: Sonically Quantifying the Content Level inside Containers'
authors:
  - Mingming Fan
  - Khai N. Truong
author_notes:
  - 
  - 
  -
  -
  -
  -
date: '2015-02-11T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2015-02-11T00:00:00Z'

# Publication type: 
# 0 = Uncategorized; 1 = Accessibility & Aging; 2 = VR/AR/Metaverse; 3 = Human-AI Collaboration; 4 = UX Methodology; 5 = Social Computing; 6 = Sensing;  
publication_types: ['6']

# Publication name and optional abbreviated publication name.
publication: In 2015 ACM International Joint Conference on Pervasive and Ubiquitous Computing (UbiComp)
publication_short: UbiComp 2015

abstract: In this paper, we present SoQr, a sensor that can be attached to an external surface of a household item to estimate the amount of content inside it. The sensor consists of a speaker and a microphone. It outputs a short duration sine wave probing sound to excite a container and its content, and then records the container’s impulse response. SoQr then extracts Mean Mel-Frequency Cepstral Coefficients from impulse response recordings of a container with different content levels and learns a support vector machine classifier. Results from a 10-fold cross validation of the prediction models on 19 common household items demonstrate that SoQr can correctly estimate the content level for these products with an average overall F-Measure above 0.96. We then further evaluated SoQr’s robustness in different usage scenarios to gain an understanding of how the system performs and specific challenges that might arise when users interact with these products and the sensor. 

# Summary. An optional shortened abstract.
summary:

keywords: Content level measurement; container; active probing; impulse response

tags:
  - Content level measurement
  - container
  - active probing
  - impulse response
featured: false

links:
  # - name: Custom Link
  #   url: http://example.org
url_pdf: 'https://www.mingmingfan.com/papers/SoQr-UbiComp2015-Fan.pdf'
# url_code: 'https://github.com/tjusenchen/Xbot'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: 'https://sites.google.com/view/mobile-accessibility/'
url_video: 'https://www.youtube.com/watch?v=el6vkFdT9Wc'

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

{{< youtube el6vkFdT9Wc >}}


