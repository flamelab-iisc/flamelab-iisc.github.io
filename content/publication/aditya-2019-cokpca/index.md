---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Anomaly detection in scientific data using joint statistical moments
subtitle: ''
summary: ''
authors:
- Konduri Aditya
- Hemanth Kolla
- W. Philip Kegelmeyer
- Timothy M. Shead
- Julia Ling
- Warren L. Davis
tags:
- Anomaly detection
- Scientific computing
- Co-kurtosis
- Tensor decomposition
- Hellinger distance
- Auto-ignition
categories: []
date: '2019-01-01'
lastmod: 2025-04-10T19:14:19+05:30
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
publishDate: '2025-04-10T13:44:18.966163Z'
publication_types:
- '2'
abstract: We propose an anomaly detection method for multi-variate scientific data
  based on analysis of high-order joint moments. Using kurtosis as a reliable measure
  of outliers, we suggest that principal kurtosis vectors, by analogy to principal
  component analysis (PCA) vectors, signify the principal directions along which outliers
  appear. The inception of an anomaly, then, manifests as a change in the principal
  values and vectors of kurtosis. Obtaining the principal kurtosis vectors requires
  decomposing a fourth order joint cumulant tensor for which we use a simple, computationally
  less expensive approach that involves performing a singular value decomposition
  (SVD) over the matricized tensor. We demonstrate the efficacy of this approach on
  synthetic data, and develop an algorithm to identify the occurrence of a spatial
  and/or temporal anomalous event in scientific phenomena. The algorithm decomposes
  the data into several spatial sub-domains and time steps to identify regions with
  such events. Feature moment metrics, based on the alignments of the principal kurtosis
  vectors, are computed at each sub-domain and time step for all features to quantify
  their relative importance towards the overall kurtosis in the data. Accordingly,
  spatial and temporal anomaly metrics for each sub-domain are proposed using the
  Hellinger distance of the feature moment metric distribution from a suitable nominal
  distribution. We apply the algorithm to two turbulent auto-ignition combustion cases
  and demonstrate that the anomaly metrics reliably capture the occurrence of auto-ignition
  in relevant spatial sub-domains at the right time steps.
publication: '*Journal of Computational Physics*'
doi: https://doi.org/10.1016/j.jcp.2019.03.003
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S002199911930172X
---
