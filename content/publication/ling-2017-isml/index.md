---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Using feature importance metrics to detect events of interest in scientific
  computing applications
subtitle: ''
summary: ''
authors:
- Julia Ling
- W. Philip Kegelmeyer
- Konduri Aditya
- Hemanth Kolla
- Kevin A. Reed
- Timothy M. Shead
- Warren L. Davis
tags:
- 'Program processors;Feature extraction;Measurement;Meteorology;Anomaly detection;Event
  detection;Decision trees;I.6.6 [Computing Methodologies]: Simulation and Modeling-Simulation
  Output Analysis;I.5.0 [Computing Methodologies]: Pattern Recognition-General'
categories: []
date: '2017-10-01'
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
publishDate: '2025-04-10T13:44:19.561320Z'
publication_types:
- '1'
abstract: 'With current high performance scientific computing workflows, data are
  typically recorded at regular intervals spaced several hundred time steps apart.
  Data are not saved at every time step to prevent excessive memory usage and because
  data I/O is often a bottleneck in the workflow. However, in many dynamical systems,
  events of interest occur locally in space and time. In these cases, a global data
  save across all processors at regular intervals is both inefficient and ineffective:
  it will result in data being saved over regions where nothing of interest is occurring,
  and it will miss an event of interest that occurs at time steps between data saves.
  What is needed is a method of automatically detecting an event of interest as it
  occurs so that a data save can be triggered on the relevant processors. We propose
  a method of detecting such events of interest using feature importance metrics.
  This method requires very little communication between processors, thereby lending
  itself to implementation in a high performance computing setting.'
publication: '*2017 IEEE 7th Symposium on Large Data Analysis and Visualization (LDAV)*'
doi: 10.1109/LDAV.2017.8231851
---
