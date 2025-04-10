---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: An asynchronous discontinuous Galerkin method for massively parallel PDE solvers
subtitle: ''
summary: ''
authors:
- Shubham K. Goswami
- Konduri Aditya
tags:
- Asynchronous schemes
- Partial differential equations
- Parallel computing
- Massive computations
- Discontinuous Galerkin method
categories: []
date: '2024-01-01'
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
publishDate: '2025-04-10T13:44:17.097369Z'
publication_types:
- '2'
abstract: The discontinuous Galerkin (DG) method is widely being used to solve hyperbolic
  partial differential equations (PDEs) due to its ability to provide high-order accurate
  solutions in complex geometries, capture discontinuities, and exhibit high arithmetic
  intensity. However, the scalability of DG-based solvers is impeded by communication
  bottlenecks arising from the data movement and synchronization requirements at extreme
  scales. To address these challenges, recent studies have focused on the development
  of asynchronous computing approaches for PDE solvers. Herein, we introduce the asynchronous
  DG (ADG) method, which combines the benefits of the DG method with asynchronous
  computing to overcome communication bottlenecks. The ADG method relaxes the need
  for data communication and synchronization at a mathematical level, allowing processing
  elements to operate independently regardless of the communication status, thus potentially
  improving the scalability of solvers. The proposed ADG method ensures flux conservation
  and effectively addresses challenges arising from asynchrony. To assess its stability,
  Fourier-mode analysis is employed to examine the dissipation and dispersion behavior
  of fully-discrete equations that use the DG and ADG schemes along with the Runge–Kutta
  (RK) time integration scheme. Furthermore, an error analysis within a statistical
  framework is presented, which demonstrates that the ADG method with standard numerical
  fluxes achieves at most first-order accuracy. To recover accuracy, we introduce
  asynchrony-tolerant (AT) fluxes that utilize data from multiple time levels. Extensive
  numerical experiments were conducted to validate the performance of the ADG-AT scheme
  for both linear and nonlinear problems. Overall, the proposed ADG-AT method demonstrates
  the potential to achieve accurate and scalable DG-based PDE solvers, paving the
  way for simulations of complex physical systems on massively parallel supercomputers.
publication: '*Computer Methods in Applied Mechanics and Engineering*'
doi: https://doi.org/10.1016/j.cma.2024.117218
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0045782524004742
---
