---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Evaluation of finite difference based asynchronous partial differential equations
  solver for reacting flows
subtitle: ''
summary: ''
authors:
- Komal Kumari
- Emmet Cleary
- Swapnil Desai
- Diego A. Donzis
- Jacqueline H. Chen
- Konduri Aditya
tags:
- Asynchronous computing
- DNS
- Combustion
- Exascale
- WENO
- Finite-difference
categories: []
date: '2023-01-01'
lastmod: 2025-04-10T19:14:17+05:30
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
publishDate: '2025-04-10T13:44:17.860952Z'
publication_types:
- '2'
abstract: Next-generation exascale machines with extreme levels of parallelism will
  provide massive computing resources for large scale numerical simulations of complex
  physical systems at unprecedented parameter ranges. However, novel numerical methods,
  scalable algorithms and re-design of current state-of-the art numerical solvers
  are required for scaling to these machines with minimal overheads. One such approach
  for partial differential equations based solvers involves computation of spatial
  derivatives with possibly delayed or asynchronous data using high-order asynchrony-tolerant
  (AT) schemes to facilitate mitigation of communication and synchronization bottlenecks
  without affecting the numerical accuracy. In the present study, an effective methodology
  of implementing temporal discretization using a multi-stage Runge-Kutta method with
  AT schemes is presented. Together these schemes are used to perform asynchronous
  simulations of canonical reacting flow problems, demonstrated in one-dimension including
  auto-ignition of a premixture, premixed flame propagation and non-premixed autoignition.
  Simulation results show that the AT schemes incur very small numerical errors in
  all key quantities of interest including stiff intermediate species despite delayed
  data at processing element (PE) boundaries. For simulations of supersonic flows,
  the degraded numerical accuracy of well-known shock-resolving WENO (weighted essentially
  non-oscillatory) schemes when used with relaxed synchronization is also discussed.
  To overcome this loss of accuracy, high-order AT-WENO schemes are derived and tested
  on linear and non-linear equations. Finally the novel AT-WENO schemes are demonstrated
  in the propagation of a detonation wave with delays at PE boundaries.
publication: '*Journal of Computational Physics*'
doi: https://doi.org/10.1016/j.jcp.2023.111906
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0021999123000013
---
