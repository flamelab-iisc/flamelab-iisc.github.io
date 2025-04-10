---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Data-driven identification of precursors of flashback in a lean hydrogen reheat
  combustor
subtitle: ''
summary: ''
authors:
- Mihnea Floris
- Tadikonda Shiva Sai
- Dibyajyoti Nayak
- Ivan Langella
- Konduri Aditya
- Nguyen Anh Khoa Doan
tags:
- Flashback
- Hydrogen combustion
- Precursor identification
- Clustering
- Featurization
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
publishDate: '2025-04-10T13:44:16.201051Z'
publication_types:
- '2'
abstract: In this work, we propose a data-driven framework to identify precursors
  of extreme events in turbulent reacting flows. Specifically, we tackle the problem
  of flashback prediction in a lean hydrogen reheat combustor. Our framework is composed
  of two parts. The first consists in the use of a co-kurtosis based approach to identify
  the components of the thermochemical and flow state which are the most relevant
  for the onset of flashback. This allows for an efficient low-dimensional representation.
  From this reduced representation, a modularity-based clustering algorithm is then
  employed to segregate between clusters which contain normal and extreme (flashbacking)
  states, and the cluster located in-between these states, which are the precursor
  states of extreme events. We show that this method is able to identify the most
  important features at the onset of flashback in the considered reheat combustor
  and then provide precursor states based on those. The prediction time obtained with
  the identified precursors is relatively large when compared to the duration over
  which the combustor is stable. Additional analyses on the specific choice of features
  for the precursor identification and the sampling locations are made. The robustness
  of the method when using shorter time series to identify the precursor is also investigated.
  Results show that the method is generally robust with respect to such changes. A
  first step towards practical measurements is also attempted with wall pressure measurements,
  which shows only a moderate reduction in prediction time. This work proposes for
  the first time a data-driven technique to automatically identify precursors of flashback
  in hydrogen combustion opening the path for such applications on other extreme events
  in reacting flows.
publication: '*Proceedings of the Combustion Institute*'
doi: https://doi.org/10.1016/j.proci.2024.105524
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S1540748924003328
---
