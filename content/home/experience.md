---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 24

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Computer Vision Engineer
    company: Momenta
    company_url: 'https://www.momenta.cn/'
    company_logo: Momenta
    location: China
    date_start: '2021-09-06'
    date_end: ''
    description: |2-
        Responsibilities include:
        * Responsible for the long-tailed class imbalance problem of traffic light detection algorithms in L4 autonomous driving.
        * Implementation of CycleGAN to conduct unsupervised data augmentation, converting traffic light bulbs from left arrow to leftUturn arrow.
        * Utilized OpenCV and mmcv to categorize and crop traffic lights bulbs from 350357 frames according to color, pattern and lighting conditions.
        * Increased the classification accuracy for leftUturn traffic light from 78.41% to 87.27%, and the mean average precision from 93.01% to 94.80%.
        
  - title: Professor of Semiconductor Physics
    company: University X
    company_url: ''
    company_logo: org-x
    location: California
    date_start: '2016-01-01'
    date_end: '2020-12-31'
    description: Taught electronic engineering and researched semiconductor physics.

design:
  columns: '2'
---
