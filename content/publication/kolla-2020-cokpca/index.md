---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Higher Order Tensors for DNS Data Analysis and Compression
subtitle: ''
summary: ''
authors:
- Hemanth Kolla
- Konduri Aditya
- Jacqueline H. Chen
tags: []
categories: []
date: '2020-01-01'
lastmod: 2025-04-10T19:14:18+05:30
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
publishDate: '2025-04-10T13:44:18.377737Z'
publication_types:
- '6'
abstract: We propose the use of higher order tensors, and their decompositions, for
  efficient analysis of combustion direct numerical simulation (DNS) data. Turbulent
  combustion DNS data, being inherently multiscale and multivariate, pose many challenges
  and higher order tensors are a natural abstraction to organise, probe and analyse
  them. The chapter gives a high-level overview of prominent tensor decomposition
  methods, their interpretation, algorithmic challenges and desirable properties.
  Two examples of DNS analysis employing tensor decompositions are then presented.
  The first analysis, based on truncated higher order singular value decomposition
  (truncated HOSVD), also known as Tucker decomposition, allows significant, albeit
  lossy, compression of DNS data, which may be inevitable in the exascale computing
  era. The factors aiding, and impeding, compression and the implications in terms
  of element-wise error distributions are presented using three candidate DNS data
  sets. The second analysis is centred on higher order joint moment tensors, which
  are richly informative for multivariate non-Gaussian variables. An anomaly detection
  algorithm based on the decomposition of the fourth moment tensor is presented, and
  its ability in detecting localised auto-ignition kernels in a homogeneous charge
  compression ignition (HCCI) data set is examined.
publication: '*Data Analysis for Direct Numerical Simulations of Turbulent Combustion:
  From Equation-Based Analysis to Machine Learning*'
doi: 10.1007/978-3-030-44718-2_6
links:
- name: URL
  url: https://doi.org/10.1007/978-3-030-44718-2_6
---
