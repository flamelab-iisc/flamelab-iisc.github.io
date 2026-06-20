---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Accuracy and scalability of asynchronous flow solver for transitional flows
subtitle: ''
summary: ''
authors:
- Aswin Kumar Arumugam
- Shubham Kumar Goswami
- Nagabhushana Rao Vadlamani
- Konduri Aditya
tags: []
categories: []
date: '2026-06-20'
lastmod: 2026-06-20T19:14:15+05:30
featured: true
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
publishDate: '2026-06-16T13:44:15.716050Z'
publication_types:
- '2'
abstract: 'To overcome the communication bottlenecks observed in state-of-the-art parallel time-dependent flow solvers at extreme scales, an asynchronous computing approach that relaxes communication and synchronization at a mathematical level was previously developed. This approach preserves high-order accuracy of computations near processing element boundaries using asynchrony-tolerant (AT) schemes while significantly improving the scalability. The numerical properties of the AT schemes were studied based on simple linear and nonlinear partial differential equations (PDEs) in previous works. Allowing asynchrony in numerical schemes can minimize communication overheads in a parallel setting in two ways: one that avoids communication over a few predetermined time steps, and the other that initiates communications without enforcing synchronization. In this study, the asynchronous algorithms are incorporated into the high-order compressible flow solver COMP-SQUARE, which solves practically relevant flow problems in complex geometries in a multi-block framework. The numerical efficacy and scalability of the two asynchronous algorithms are demonstrated for three test cases: isentropic advection of a vortex, the Taylor–Green vortex, and a much more sensitive case of the flow transitioning on a NACA0012 airfoil. Speed-ups of up to 4x with respect to the baseline synchronous algorithm are observed in the scaling experiments performed on up to 18,432 cores. The results of this study demonstrate the applicability of AT schemes on established CFD solvers to improve scalability at extreme scales as the scientific computing environment moves to the exascale era.'
publication: '*Computers and Fluids*'
doi: https://doi.org/10.1016/j.compfluid.2026.107189
links:
- name: URL
  url: https://doi.org/10.1016/j.compfluid.2026.107189
---
