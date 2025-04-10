---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Asynchronous finite-difference schemes for partial differential equations
subtitle: ''
summary: ''
authors:
- Diego A. Donzis
- Konduri Aditya
tags:
- Asynchronous schemes
- Partial differential equations
- Massive computations
categories: []
date: '2014-01-01'
lastmod: 2025-04-10T19:14:20+05:30
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
publishDate: '2025-04-10T13:44:20.028849Z'
publication_types:
- '2'
abstract: Current trends in massively parallel computing systems suggest that the
  number of processing elements (PEs) used in simulations will continue to grow over
  time. A known problem in this context is the overhead associated with communication
  and/or synchronization between PEs as well as idling due to load imbalances. Simulation
  at extreme levels of parallelism will then require an elimination, or at least a
  tight control of these overheads. In this work, we present an analysis of common
  finite difference schemes for partial differential equations (PDEs) when no synchronization
  between PEs is enforced. PEs are allowed to continue computations regardless of
  messages status and are thus asynchronous. We show that while stability is conserved
  when these schemes are used asynchronously, accuracy is greatly degraded. Since
  message arrivals at PEs are essentially random processes, so is the behavior of
  the error. Within a statistical framework we show that average errors drop always
  to first-order regardless of the original scheme. The value of the error is found
  to depend on both grid spacing as well as characteristics of the computing system
  including number of processors and statistics of the delays. We propose new schemes
  that are robust to asynchrony. The analytical results are compared against numerical
  simulations.
publication: '*Journal of Computational Physics*'
doi: https://doi.org/10.1016/j.jcp.2014.06.017
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0021999114004240
---
