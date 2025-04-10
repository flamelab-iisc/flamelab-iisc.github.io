---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: A co-kurtosis based dimensionality reduction method for combustion datasets
subtitle: ''
summary: ''
authors:
- Anirudh Jonnalagadda
- Shubham Kulkarni
- Akash Rodhiya
- Hemanth Kolla
- Konduri Aditya
tags:
- Dimensionality reduction
- Principal component analysis
- Co-kurtosis tensor
- Independent component analysis
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
publishDate: '2025-04-10T13:44:17.493626Z'
publication_types:
- '2'
abstract: Principal Component Analysis (PCA) is a dimensionality reduction technique
  widely used to reduce the computational cost associated with numerical simulations
  of combustion phenomena. However, PCA, which transforms the thermo-chemical state
  space based on eigenvectors of co-variance of the data, could fail to capture information
  regarding important localized chemical dynamics, such as the formation of ignition
  kernels, appearing as extreme-valued samples in a dataset. In this paper, we propose
  an alternate dimensionality reduction procedure, co-kurtosis PCA (CoK-PCA), wherein
  the required principal vectors are computed from a high-order joint statistical
  moment, namely the co-kurtosis tensor, which may better identify directions in the
  state space that represent stiff dynamics. We first demonstrate the potential of
  the proposed CoK-PCA method using a synthetically generated dataset that is representative
  of typical combustion simulations. Thereafter, we characterize and contrast the
  accuracy of CoK-PCA against PCA for datasets representing spontaneous ignition of
  premixed ethylene-air in a simple homogeneous reactor and ethanol-fueled homogeneous
  charged compression ignition (HCCI) engine. Specifically, we compare the low-dimensional
  manifolds in terms of reconstruction errors of the original thermo-chemical state,
  and species production and heat release rates computed from the linearly reconstructed
  state. The latter – a comparison of species production and heat release rates –
  is a more rigorous assessment of the accuracy of dimensionality reduction. We find
  that, for the simplistic linear reconstruction, the co-kurtosis based reduced manifold
  represents the original thermo-chemical state more accurately than PCA, especially
  in the regions where chemical reactions are important.
publication: '*Combustion and Flame*'
doi: https://doi.org/10.1016/j.combustflame.2023.112635
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0010218023000202
---
