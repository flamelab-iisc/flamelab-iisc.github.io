---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Modeling subgrid scale production rates on complex meshes using graph neural networks
subtitle: ''
summary: ''
authors:
- Priyabrat Dash
- Mathis Bode
- Konduri Aditya
tags: 
- Fluid Dynamics
- Machine Learning
categories: []
date: '2026-03-20'
lastmod: 2026-04-01T15:34:19+05:30
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
publishDate: '2026-04-01T10:04:19.000000Z'
publication_types:
- '3'
abstract: 'Large-eddy simulations (LES) require closures for filtered production rates because the resolved fields do not contain all correlations that govern chemical source terms. We develop a graph neural network (GNN) that predicts filtered species production rates on non-uniform meshes from inputs of filtered mass fractions and temperature. Direct numerical simulations of turbulent premixed hydrogen-methane jet flames with hydrogen fractions of 10%, 50%, and 80% provide the dataset. All fields are Favre filtered with the filter width matched to the operating mesh, and learning is performed on subdomain graphs constructed from mesh-point connectivity. A compact set of reactants, intermediates, and products is used, and their filtered production rates form the targets. The model is trained on 10% and 80% blends and evaluated on the unseen 50% blend to test cross-composition generalization. The GNN is compared against an unclosed reference that evaluates rates at the filtered state, and a convolutional neural network baseline that requires remeshing. Across in-distribution and out-of-distribution cases, the GNN yields lower errors and closer statistical agreement with the reference data. Furthermore, the model demonstrates robust generalization across varying filter widths without retraining, maintaining bounded errors at coarser spatial resolutions. A backward facing step configuration further confirms prediction efficacy on a practically relevant geometry. These results highlight the capability of GNNs as robust data-driven closure models for LES on complex meshes.'
publication: '*arXiv*'
doi: 10.48550/ARXIV.2603.19841
links:
- name: URL
  url: https://arxiv.org/abs/2603.19841
---
