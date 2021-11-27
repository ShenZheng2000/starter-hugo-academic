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
    location: Suzhou, China
    date_start: '2021-09-06'
    date_end: ''
    description: |2-
      * Responsible for the long-tailed class imbalance problem of traffic light detection algorithms in L4 autonomous driving.
      * Implementation of CycleGAN to conduct unsupervised data augmentation, converting traffic light bulbs from left arrow to leftUturn arrow.
      * Utilized OpenCV and mmcv to categorize and crop traffic lights bulbs from 350357 frames according to color, pattern and lighting conditions.
      * Increased the classification accuracy for leftUturn traffic light from 78.41% to 87.27%, and the mean average precision from 93.01% to 94.80%.
        
  - title: Research Assistant
    company: University of Notre Dame
    company_url: 'https://www.nd.edu/'
    company_logo: UND
    location: Notre Dame, USA
    date_start: '2021-07-05'
    date_end: '2020-09-05'
    description: |2-
      * Developed

design:
  columns: '2'
---
