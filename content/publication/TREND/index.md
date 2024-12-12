---
title: "TREND: Unsupervised 3D Representation Learning via Temporal Forecasting for LiDAR Perception“
authors:
  - Runjian Chen
  - Hyoungseob Park
  - Bo Zhang
  - Wenqi Shao
  - Ping Luo
  - Alex Wong
author_notes: []
publication_short: ""
abstract: Labeling LiDAR point clouds is notoriously time-and-energy-consuming, which spurs recent unsupervised 3D representation learning methods to alleviate the labeling burden in LiDAR perception via pretrained weights. Almost all existing work focus on a single frame of LiDAR point cloud and neglect the temporal LiDAR sequence, which naturally accounts for object motion (and their semantics). Instead, we propose TREND, namely Temporal REndering with Neural fielD, to learn 3D representation via forecasting the future observation in an unsupervised manner. Unlike existing work that follows conventional contrastive learning or masked auto encoding paradigms, TREND integrates forecasting for 3D pre-training through a Recurrent Embedding scheme to generate 3D embedding across time and a Temporal Neural Field to represent the 3D scene, through which we compute the loss using differentiable rendering. To our best knowledge, TREND is the first work on temporal forecasting for unsupervised 3D representation learning. We evaluate TREND on downstream 3D object detection tasks on popular datasets, including NuScenes, Once and Waymo. Experiment results show that TREND brings up to 90\% more improvement as compared to previous SOTA unsupervised 3D pre-training methods and generally improve different downstream models across datasets, demonstrating that indeed temporal forecasting brings improvement for LiDAR perception.
tags:
  - Unsupervised 3D Representation Learning
  - Temporal Rendering
  - Autonomous Driving
projects: []
slides: ""
url_pdf: "https://arxiv.org/pdf/2412.03054"
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
