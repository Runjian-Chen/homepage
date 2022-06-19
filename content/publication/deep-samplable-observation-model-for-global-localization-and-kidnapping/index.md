---
title: Deep Samplable Observation Model for Global Localization and Kidnapping
publication_types:
  - "2"
authors:
  - "**Runjian Chen**"
  - Huan Yin
  - Yanmei Jiao
  - Gamini Dissanayake
  - Yue Wang
  - and Rong Xiong
publication: IEEE ROBOTICS AND AUTOMATION LETTERS (RA-L)
abstract: "Global localization and kidnapping are two challenging problems in
  robot localization. The popular method, Monte Carlo Localization (MCL)
  addresses the problem by iteratively updating a set of particles with a
  “sampling-weighting” loop. Sampling is decisive to the performance of MCL [1].
  However, traditional MCL can only sample from a uniform distribution over the
  state space. Although variants of MCL propose different sampling models, they
  fail to provide an accurate distribution or generalize across scenes. To
  better deal with these problems, we present a distribution proposal model
  named Deep Samplable Observation Model (DSOM). DSOM takes a map and a 2D laser
  scan as inputs and outputs a conditional multimodal probability distribution
  of the pose, making the samples more focusing on the regions with higher
  likelihood. With such samples, the convergence is expected to be more
  effective and efficient. Considering that the learning-based sampling model
  may fail to capture the accurate pose sometimes, we furthermore propose the
  Adaptive Mixture MCL (AdaM MCL), which deploys a trusty mechanism to
  adaptively select updating mode for each particle to tolerate this situation.
  Equipped with DSOM, AdaM MCL can achieve more accurate estimation, faster
  convergence and better scalability than previous methods in both synthetic and
  real scenes. Even in real environments with long-term changes, AdaM MCL is
  able to localize the robot using DSOM trained only by simulation observations
  from a SLAM map or a blueprint map. Source code for this paper is available
  here: https://github.com/Runjian-Chen/AdaM_MCL."
draft: false
featured: true
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
date: 2022-06-19T14:38:19.446Z
---
