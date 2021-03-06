---
title: "Deblur-YOLO: Real-Time Object Detection with Efficient Blind Motion Deblurring"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Yuxiong Wu
- Shiyu Jiang
- Changjie Lu
- Gaurav Gupta

# Author notes (optional)
author_notes:
- ""
- ""

date: "2021-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-09-23T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Joint Conference on Neural Networks*
publication_short: In *IJCNN 2021*

abstract: Object detection has been a traditional yet open computer vision research field. In intensive studies, object detection models have achieved promising results regarding recognition accuracy and inference speed. However, previous state-of-the-art algorithms fail to operate at blurry images. In this work, we propose Deblur-YOLO, an efficient, YOLO-based and detection-driven approach robust to motion blur photographs. We introduce a generative adversarial network with a dilated feature pyramid generator, a pair of multi-scale discriminators with spectral normalization, and a detection discriminator. We design a new image quality metric called Smooth Peak Signal-to-Noise Ratio (SPSNR) for measuring the smoothness of the reconstructed image. Empirical studies on benchmark datasets demonstrate Deblur-YOLO's superiority. On COCO 2014, Set 5 and Setl4, Deblur-YOLO achieves leading results for parameters, deblurring time, PSNR, SPSNR and SSIM. We also visually display the excellence of our deblurring performance to competing models.

# Summary. An optional shortened abstract.
summary: A detection-driven generative adversarial network for joint motion deblurring and object detection. 

# ??????tag??????????????????????????????publication?????????????????????project????????????????????????????????????????????????????????????
tags: ["Computer Vision"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# ?????????
url_pdf: ''
url_code: 'https://github.com/ShenZheng2000/Deblur-YOLO'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://github.com/ShenZheng2000/starter-hugo-academic/blob/master/content/publication/DeblurYOLO/Slides_DeblurYOLO.pdf'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# ?????????????????????project
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---




