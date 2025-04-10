---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: An asynchronous discontinuous-Galerkin method for solving PDEs at extreme scales
subtitle: ''
summary: ''
authors:
- Shubham K. Goswami
- Konduri Aditya
tags: []
categories: []
date: '2022-01-01'
lastmod: 2025-04-10T19:14:18+05:30
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2025-04-10T13:44:17.978811Z'
publication_types:
- '6'
abstract: ' View Video Presentation: https://doi.org/10.2514/6.2022-4165.vidMassively
  parallel simulations based on discontinuous-Galerkin (DG) PDE solvers often show
  poor scalability at extreme scales. This is mainly attributed to data communication
  and synchronization between different processing elements (PEs). This paper presents
  an asynchronous DG method that relaxes communication/synchronization at a mathematical
  level and allows computations at PEs to proceed regardless of the communication
  status, thus increasing the computation-communication overlap. We show that standard
  DG schemes under relaxed synchronization result in a loss of conservation property
  and provide solutions that are at most first-order accurate. Subsequently, we describe
  a simple method to preserve conservation and develop new asynchrony-tolerant (AT)
  fluxes that provide high-order accurate solutions. Results from simulations of one-dimensional
  linear and nonlinear equations are presented to verify the accuracy of the asynchronous
  DG method. '
publication: '*AIAA AVIATION 2022 Forum*'
doi: 10.2514/6.2022-4165
links:
- name: URL
  url: https://arc.aiaa.org/doi/abs/10.2514/6.2022-4165
---
