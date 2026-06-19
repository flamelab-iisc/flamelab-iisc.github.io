---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: An a-posteriori analysis of co-kurtosis PCA based dimensionality reduction
  using a neural ODE solver
subtitle: ''
summary: ''
authors:
- Tadikonda Shiva Sai
- Hemanth Kolla
- Konduri Aditya
tags: []
categories: []
date: '2026-06-19'
lastmod: 2026-06-19T19:14:15+05:30
featured: true
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
publishDate: '2026-06-18T13:44:15.587478Z'
publication_types:
- '2'
abstract: 'A low-dimensional representation of thermochemical scalars based on cokurtosis principal component analysis (CoK-PCA) has been shown to effectively capture stiff chemical dynamics in reacting flows relative to the widely used principal component analysis (PCA). The effectiveness of the reduced manifold was evaluated in a priori analyses using both linear and nonlinear reconstructions of thermochemical scalars from aggressively truncated principal components (PCs). In this study, we demonstrate the efficacy of a CoK-PCA-based reduced manifold using a posteriori analysis. Simulations of spontaneous ignition in a homogeneous reactor that pose a challenge in accurately capturing the ignition delay time as well as the scalar profiles within the reaction zone are considered. The governing ordinary differential equations (ODEs) in the PC space were evolved from the initial conditions using two ODE solvers. First, a standard ODE solver that uses a pretrained artificial neural network (ANN) to estimate the source terms and integrates the solution in time. Second, a neural ODE solver that incorporates the time integration of PCs into the ANN training. The time-evolved profiles of the PCs and reconstructed thermochemical scalars demonstrate the robustness of the CoK-PCA-based low-dimensional manifold in accurately capturing the ignition process. Furthermore, we observed that the neural ODE solver significantly minimized the propagation of modeling errors across time steps and provided more accurate results than the standard ODE solver. The results of this study demonstrate the potential of CoK-PCA-based manifolds to be implemented in massively parallel reacting flow solvers.'
publication: 'Combustion Science and Technology'
doi: https://doi.org/10.1080/00102202.2026.2687139
links:
- name: URL
  url: https://doi.org/10.1080/00102202.2026.2687139
---
