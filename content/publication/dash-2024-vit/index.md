---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: A Deep Learning Based Model for Identifying Recirculation Zones From Experimental
  Images of Trapped Vortex Combustors
subtitle: ''
summary: ''
authors:
- Priyabrat Dash
- Tanaya Mallik
- Nikhil Verma
- Aritra Roy Choudhury
- R. V. Ravikrishna
- Konduri Aditya
tags: []
categories: []
date: '2024-06-01'
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
publishDate: '2025-04-10T13:44:16.833062Z'
publication_types:
- '0'
abstract: Particle image velocimetry (PIV) is a standard method for studying primary
  recirculation zones in trapped vortex combustors (TVCs), which can operate in an
  RQL configuration. However, its intrusive nature can disrupt the flow, flame, and
  equipment in compact combustors, leading to inaccuracies. As an alternative, we
  use deep learning models based on generative adversarial networks (GAN, a widely
  used approach) and vision transformers (ViT, a recently devised promising architecture)
  to estimate the position and overall structure of large-scale vortices from a non-invasively
  measured quantity, such as the planar laser-induced fluorescence (PLIF) of a species.
  These models are trained using datasets from large-eddy simulations (LES) of TVCs
  with information regarding all scalars constituting the state variable, with the
  addition of noise to mimic experimental data. Quantitative metrics such as relative
  errors and PDFs of velocity components and their orientation have been used to demonstrate
  that the ViT exhibits better performance than the GAN. Sensitivity to the type of
  noise added to simulation data during training is studied as well. The trained model
  is then used to infer velocity vectors from noisy OH-PLIF data. In the absence of
  ground truth for that case, qualitative observations reinforce our earlier notion
  of the superiority of ViT. Such models will facilitate intelligent data fusion and
  the development of digital twins of combustors.
publication: ''
doi: 10.1115/GT2024-127369
links:
- name: URL
  url: https://doi.org/10.1115/GT2024-127369
---
