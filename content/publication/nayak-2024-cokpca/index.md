---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: A co-kurtosis PCA based dimensionality reduction with nonlinear reconstruction
  using neural networks
subtitle: ''
summary: ''
authors:
- Dibyajyoti Nayak
- Anirudh Jonnalagadda
- Uma Balakrishnan
- Hemanth Kolla
- Konduri Aditya
tags:
- Dimensionality reduction
- Principal component analysis
- Co-kurtosis tensor
- Deep neural networks
- Reconstruction
categories: []
date: '2024-01-01'
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
publishDate: '2025-04-10T13:44:16.323410Z'
publication_types:
- '2'
abstract: 'For turbulent reacting flow systems, identification of low-dimensional
  representations of the thermo-chemical state space is vitally important, primarily
  to significantly reduce the computational cost of device-scale simulations. Principal
  component analysis (PCA), and its variants, are a widely employed class of methods.
  Recently, an alternative technique that focuses on higher-order statistical interactions,
  co-kurtosis PCA (CoK-PCA), has been shown to effectively provide a low-dimensional
  representation by capturing the stiff chemical dynamics associated with spatiotemporally
  localized reaction zones. While its effectiveness has only been demonstrated based
  on a priori analyses with linear reconstruction, in this work, we employ nonlinear
  techniques to reconstruct the full thermo-chemical state and evaluate the efficacy
  of CoK-PCA compared to PCA. Specifically, we combine a CoK-PCA-/PCA-based dimensionality
  reduction (encoding) with an artificial neural network (ANN) based reconstruction
  (decoding) and examine, a priori, the reconstruction errors of the thermo-chemical
  state. In addition, we evaluate the errors in species production rates and heat
  release rates, which are nonlinear functions of the reconstructed state, as a measure
  of the overall accuracy of the dimensionality reduction technique. We employ four
  datasets to assess CoK-PCA/PCA coupled with ANN-based reconstruction: zero-dimensional
  (homogeneous) reactor for autoignition of an ethylene/air mixture that has conventional
  single-stage ignition kinetics, a dimethyl ether (DME)/air mixture which has two-stage
  (low and high temperature) ignition kinetics, a one-dimensional freely propagating
  premixed ethylene/air laminar flame, and a two-dimensional dataset representing
  turbulent autoignition of ethanol in a homogeneous charge compression ignition (HCCI)
  engine. Results from the analyses demonstrate the robustness of the CoK-PCA based
  low-dimensional manifold with ANN reconstruction in accurately capturing the data,
  specifically from the reaction zones.'
publication: '*Combustion and Flame*'
doi: https://doi.org/10.1016/j.combustflame.2023.113192
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0010218023005667
---
