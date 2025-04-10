---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: A scale-similarity based workflow for self-supervised reconstruction of small-scales
  in turbulence using deep learning
subtitle: ''
summary: ''
authors:
- Priyabrat Dash
- Konduri Aditya
tags: []
categories: []
date: '2024-07-01'
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
publishDate: '2025-04-10T13:44:16.575118Z'
publication_types:
- '2'
abstract: Deep learning has been extensively utilized for modeling and analysis of
  fluid turbulence. One such application is the use of super-resolution (SR) algorithms
  to reconstruct small-scale structures from their large-scale counterparts for turbulent
  flows. To date, all SR algorithms have been supervised or require unpaired reference
  data at a high resolution for training. This renders the model inapplicable to practical
  fluid flow scenarios, in which the generation of a high-resolution ground truth
  by resolving all scales down to the Kolmogorov scale becomes prohibitive. Hence,
  it is imperative to develop physics-guided models that exploit the multiscale nature
  of turbulence. Considering SR as a state-estimation problem, we present a self-supervised
  workflow based on deep neural networks to reconstruct small-scale structures that
  are relevant to homogeneous isotropic turbulence. In addition to visual similarity,
  we assessed the quality of the obtained reconstruction using spectra, structure
  functions, and probability density functions of the gradients of velocity and a
  passive scalar. From the analysis, we infer that the outputs of the workflow are
  in statistical agreement with the ground truth, for which the training pipeline
  is agnostic. Insights into learnability, interpretability, and generality of the
  trained networks have been provided as well. The results of this study can be leveraged
  to devise techniques for the reconstruction of small-scale structures using large-eddy
  simulation data.
publication: '*Physics of Fluids*'
doi: 10.1063/5.0216747
links:
- name: URL
  url: https://doi.org/10.1063/5.0216747
---
