---
title: "Efficient Ensemble Sparse Convolutional Neural Networks with Dynamic Batch Size"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Liwei Wang
- Gaurav Gupta

# Author notes (optional)
author_notes:


date: "2020-12-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-09-23T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Computer Vision and Image Processing*
publication_short: In *CVIP*

abstract: In this paper, an efficient ensemble sparse Convolutional Neural Networks (CNNs) with dynamic batch size is proposed. We addressed two issues at the heart of deep learning—speed and accuracy. Firstly, we presented ensemble CNNs with weighted average stacking which significantly increases the testing accuracy. Secondly, we combine network pruning and Winograd-ReLU convolution to accelerate computational speed. Motivated by electron movement in electrical fields, we finally propose a novel, dynamic batch size algorithm. We repeatedly increase the learning rate and the momentum coefficient until validation accuracy falls, while scaling the batch size. With no data augmentation and little hyperparameter tuning, our method speeds up models on FASHION-MINST, CIFAR-10, and CIFAR-100 to 1.55x, 2.86x, and 4.15x with a testing accuracy improvement of 2.66%, 1.37%, and 4.48%, respectively. We also visually demonstrate that our approach retains the most distinct image classification features during exhaustive pruning.

# Summary. An optional shortened abstract.
summary: An efficient ensemble sparse Convolutional Neural Networks with dynamic batch size 

# 这个tag就是下面的词云，每个publication都可以加上，在project这边也会有，所有那个词云能联想到所有项目
tags: ["Computer Vision"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# 不用填
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# 这里可以联想到project
projects:
- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
这里给你填abstract啥的
如果你想加链节
比如
Click here to see [url](https://ieeexplore.ieee.org/document/9534352).
这个格式
