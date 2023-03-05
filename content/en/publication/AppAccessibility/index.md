---
title: Accessibile or Not? An Empirical Investigation of Android App Accessibility
authors:
  - Sen Chen
  - Chunyang Chen
  - Lingling Fan
  - Mingming Fan
  - Xian Zhan 
  - Yang Liu
author_notes:
  - 
  - 
  -
  -
  -
  -
date: '2021-12-05T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2021-12-05T00:00:00Z'

# Publication type: 
# 0 = Uncategorized; 1 = Accessibility & Aging; 2 = VR/AR/Metaverse; 3 = Human-AI Collaboration; 4 = UX Methodology; 5 = Social Computing; 6 = Sensing;  
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Software Engineering 2021
publication_short: TSE 2021

abstract: Mobile apps provide new opportunities to people with disabilities to act independently in the world. Following the law of theUS, EU, mobile OS vendors such as Google and Apple have included accessibility features in their mobile systems and provide a set of guidelines and toolsets for ensuring mobile app accessibility. Motivated by this trend, researchers have conducted empirical studies by using the inaccessibility issue rate of each page (i.e., screen level) to represent the characteristics of mobile app accessibility. However, there still lacks an empirical investigation directly focusing on the issues themselves (i.e., issue level) to unveil more fine-grained findings, due to the lack of an effective issue detection method and a relatively comprehensive dataset of issues. To fill in this literature gap, we first propose an automated app page exploration tool, named Xbot, to facilitate app accessibility testing and automatically collect accessibility issues by leveraging the instrumentation technique and static program analysis. Owing to the relatively high activity coverage (around 80%) achieved by Xbot when exploring apps, Xbot achieves better performance on accessibility issue collection than existing testing tools such as Google Monkey. With Xbot, we are able to collect a relatively comprehensive accessibility issue dataset and finally collect 86,767 issues from 2,270 unique apps including both closed-source and open-source apps, based on which we further carry out an empirical study from the perspective of accessibility issues themselves to investigate novel characteristics of accessibility issues. Specifically, we extensively investigate these issues by checking 1) the overall severity of issues with multiple criteria, 2) the in-depth relation between issue types and app categories, GUI component types, 3) the frequent issue patterns quantitatively, and 4) the fixing status of accessibility issues. Finally, we highlight some insights to the community and hope to raise the attention to maintaining mobile app accessibility for users especially the elderly and disabled.

# Summary. An optional shortened abstract.
summary:

keywords: Mobile Accessibility, Empirical Study, Automated Accessibility Testing, Android App, Xbot

tags:
  - Mobile Accessibility
  - Empirical Study
  - Automated Accessibility Testing
  - Android App
  - Xbot
featured: false

links:
  # - name: Custom Link
  #   url: http://example.org
url_pdf: 'https://www.mingmingfan.com/papers/AppAccessibility-TSE21.pdf'
url_code: 'https://github.com/tjusenchen/Xbot'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
url_source: 'https://sites.google.com/view/mobile-accessibility/'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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

<!-- {{< youtube f9lO9tin4tw >}} -->


