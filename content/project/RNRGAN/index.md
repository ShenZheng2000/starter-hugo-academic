---
title: Riemannian Noise Robust Generative Adversarial Network with Stochastic Bounds
summary: a Generative Adversarial Network for image generation from unspecified noisy data.
tags:
- Deep Learning
- Computer Vision
date: "2020-10-01T00:00:00Z"
# tags就是project会归类到哪里，可以有多个tag

# Optional external URL for project (replaces project detail page).
external_link: ""

# caption就相当于reference，这个图片是哪里来的，会显示在图像右下角
image:
  caption: ''
  focal_point: Smart

# 不要用url_X，直接加icon，如果paper可以加笔啥的，参考我的
links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
# slide可以暂时不要

---
类似简介abstract
Generative Adversarial Network has achieved promising results for image generation tasks on benchmark datasets. However, those GAN models tend to generate images with fidelity when the training images are corrupted by noise. Recent methods like AmbientGAN and NRGAN either assume that the noise distribution is given or suffer from training instability. This restricts their application to real-world images accompanied by unspecified noise. In this paper, we propose a new architecture called Riemannian Noise Robust Generative Adversarial Network (RNRGAN), an image generation model robust to various types of noisy training images. Based upon NRGAN, RNRGAN replaces the Euclidian metric with the Riemannian metric for the loss function. This strategy imposes restrictions for the GAN objective function, thereby stabilizing the training process. We then exploit the reparameterization trick and propose a noise transformation technique to address different noise distributions and amounts. To ease the hyperparameter tuning process, we replace gradient penalty terms with a dynamic boundary which helps our model attains faster, better, and smoother convergence. Qualitative and Quantitative Comparisons demonstrate that RNRGAN outperforms various state-of-the-art image generators from noisy samples on the STL-10 and CelebA datasets. 
