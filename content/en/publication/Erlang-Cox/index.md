---
title: 'Augmenting Gesture Recognition with Erlang-Cox Models to Identify Neurological Disorders in Premature Babies'
authors:
  - Mingming Fan
  - Dana Gravem
  - Dan Cooper
  - Donald J Patterson
author_notes:
  - 
  - 
  -
  -
  -
  -
date: '2012-02-11T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2012-02-11T00:00:00Z'

# Publication type: 
# 0 = Uncategorized; 1 = Accessibility & Aging; 2 = VR/AR/Metaverse; 3 = Human-AI Collaboration; 4 = UX Methodology; 5 = Social Computing; 6 = Sensing; 
publication_types: ['6']

# Publication name and optional abbreviated publication name.
publication: In 2012 ACM Conference on Ubiquitous Computing (UbiComp'12), pp411-420.
publication_short: UbiComp 2012

abstract: In this paper we demonstrate a Markov model based technique for recognizing gestures from accelerometers that explicitly represents duration. We do this by embedding an Erlang-Cox state transition model, which has been shown to accurately represent the first three moments of a general distribution, within a Dynamic Bayesian Network (DBN). The transition probabilities in the DBN can be learned via Expectation-Maximization or by using closed-form solutions. We test this modeling technique on 10 hours of data collected from accelerometers worn by babies pre-categorized as high-risk in the Newborn Intensive Care Unit (NICU) at UCI. We show that by treating instantaneous machine learning classification values as observations and explicitly modeling duration, we improve the recognition of Cramped Synchronized General Movements, a motion highly correlated with an eventual diagnosis of Cerebral Palsy.

# Summary. An optional shortened abstract.
summary:

keywords: Gesture Recognition, Health, Sensors, User Modeling

tags:
  - Gesture Recognition
  - Health
  - Sensors
  - User Modeling
featured: false

links:
  # - name: Custom Link
  #   url: http://example.org
url_pdf: 'https://www.mingmingfan.com/papers/Ubicomp12_MingmingFan.pdf'
# url_code: 'https://github.com/tjusenchen/Xbot'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: 'https://sites.google.com/view/mobile-accessibility/'
url_video: 'https://www.youtube.com/watch?v=WpW_zPow_zM'

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

{{< youtube WpW_zPow_zM >}}


