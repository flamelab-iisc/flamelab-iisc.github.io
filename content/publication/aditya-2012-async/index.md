---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: ' Poster: Asynchronous Computing for Partial Differential Equations at Extreme
  Scales '
subtitle: ''
summary: ''
authors:
- Aditya Konduri
- Diego A. Donzis
tags:
- ''
categories: []
date: '2012-11-01'
lastmod: 2025-04-10T19:14:20+05:30
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
publishDate: '2025-04-10T13:44:20.288643Z'
publication_types:
- '1'
abstract: ' Advances in computing technology have made numerical simulations an indispensable
  research tool in the pursuit of understanding real life problems. Due to their complexity,
  these simulations demand massive computations with extreme levels of parallelism.
  At extreme scales, communication between processors could take up a substantial
  amount of time. This results in substantial waste in computing cycles, as processors
  remain idle for most of the time. We investigate a novel approach based on widely
  used finite-difference schemes in which computations are carried out in an asynchronous
  fashion---synchronization among cores is not enforced and computations proceed regardless
  of the status of messages. This drastically reduces idle times resulting in much
  larger computation rates and scalability. However, stability, consistency and accuracy
  have to be shown in order for these schemes to be viable. This is done through mathematical
  theory and numerical simulations. Results are used to design new numerical schemes
  robust to asynchronicity. '
publication: '* 2012 SC Companion: High Performance Computing, Networking, Storage
  and Analysis (SCC) *'
doi: 10.1109/SC.Companion.2012.247
links:
- name: URL
  url: https://doi.ieeecomputersociety.org/10.1109/SC.Companion.2012.247
---
