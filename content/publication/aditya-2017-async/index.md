---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: High-order asynchrony-tolerant finite difference schemes for partial differential
  equations
subtitle: ''
summary: ''
authors:
- Konduri Aditya
- Diego A. Donzis
tags:
- Asynchrony-tolerant schemes
- Partial differential equations
- Massive computations
- Asynchronous computing
categories: []
date: '2017-01-01'
lastmod: 2025-04-10T19:14:19+05:30
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
publishDate: '2025-04-10T13:44:19.680841Z'
publication_types:
- '2'
abstract: Synchronizations of processing elements (PEs) in massively parallel simulations,
  which arise due to communication or load imbalances between PEs, significantly affect
  the scalability of scientific applications. We have recently proposed a method based
  on finite-difference schemes to solve partial differential equations in an asynchronous
  fashion – synchronization between PEs is relaxed at a mathematical level. While
  standard schemes can maintain their stability in the presence of asynchrony, their
  accuracy is drastically affected. In this work, we present a general methodology
  to derive asynchrony-tolerant (AT) finite difference schemes of arbitrary order
  of accuracy, which can maintain their accuracy when synchronizations are relaxed.
  We show that there are several choices available in selecting a stencil to derive
  these schemes and discuss their effect on numerical and computational performance.
  We provide a simple classification of schemes based on the stencil and derive schemes
  that are representative of different classes. Their numerical error is rigorously
  analyzed within a statistical framework to obtain the overall accuracy of the solution.
  Results from numerical experiments are used to validate the performance of the schemes.
publication: '*Journal of Computational Physics*'
doi: https://doi.org/10.1016/j.jcp.2017.08.037
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0021999117306149
---
