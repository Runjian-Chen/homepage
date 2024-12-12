---
title: "CLAP: Unsupervised 3D Representation Learning for Fusion 3D Perception via Curvature Sampling and Prototype Learning"
authors:
  - Runjian Chen
  - Hang Zhang
  - Avinash Ravichandran
  - Wenqi Shao
  - Alex Wong
  - Ping Luo
author_notes: []
publication_short: ""
abstract: Unsupervised 3D representation learning via masked-and-reconstruction with differentiable rendering is promising to reduce the labeling burden for fusion 3D perception. However, previous literature conduct pre-training for different modalities separately because of the hight GPU memory consumption. Consequently, the interaction between the two modalities (images and point clouds) is neglected during pre-training. In this paper, we explore joint unsupervised pre-training for fusion 3D perception via differentiable rendering and propose CLAP, short for Curvature sampLing and swApping Prototype assignment prediction. The contributions are three-fold. 1) To overcome the GPU memory consumption problem, we propose Curvature Sampling to sample the more informative points/pixels for pre-training. 2) We propose to use learnable prototypes to represent parts of the scenes in a common feature space and bring the idea of swapping prototype assignment prediction to learn the interaction between the two modalities. 3) To further optimize learnable prototypes, we propose an Expectation-Maximization training scheme to maximize the similarity between embeddings and prototypes, followed by a Gram Matrix Regularization Loss to avoid collapse. Experiment results on NuScenes show that CLAP achieves 300\% more performance gain as compared to previous SOTA 3D pre-training method via differentiable rendering.
tags:
  - Unsupervised Representation Learning
  - Autonomous Driving
projects: []
slides: ""
url_pdf: ""
publication_types:
  - "3"
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: featured.png
summary: ""
url_dataset: ""
url_project: ""
url_source: ""
url_video: ""
publication: ""
featured: true
date: 2024-12-12T00:00:00.000Z
url_slides: ""
publishDate: 2024-12-12T00:00:00.000Z
url_poster: ""
url_code: ""
doi: ""
---
