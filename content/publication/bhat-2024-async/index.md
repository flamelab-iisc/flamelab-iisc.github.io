---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Building a portable parallel asynchronous PDE solver using Kokkos
subtitle: ''
summary: ''
authors:
- Ranjan Bhat
- Konduri Aditya
tags:
- Scalability;Partial differential equations;High performance computing;Conferences;Buildings;Computer
  architecture;Benchmark testing;Libraries;Performance analysis;Finite difference
  methods;Kokkos;portability;scalability;asynchonry-tolerant schemes
categories: []
date: '2024-12-01'
lastmod: 2025-04-10T19:14:16+05:30
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
publishDate: '2025-04-10T13:44:15.945352Z'
publication_types:
- '1'
abstract: In this study, we outline the design and implementation of a portable massively
  parallel asynchronous solver for time-dependent partial differential equations (PDEs).
  The solver is implemented using Kokkos library for portability across different
  node architectures and is coupled with the communication-avoiding algorithm that
  relaxes the communication across nodes, thus improving the scalability. Asynchrony-tolerant
  finite difference schemes for spatial derivatives along with the low storage Runge-Kutta
  scheme for time integration are used to achieve high-order accuracy. The efficacy
  of the implementation is demonstrated using a mini-app that solves the three-dimensional
  diffusion problem.
publication: '*2024 IEEE 31st International Conference on High Performance Computing,
  Data and Analytics Workshop (HiPCW)*'
doi: 10.1109/HiPCW63042.2024.00048
---
