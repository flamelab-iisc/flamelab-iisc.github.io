---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'ChemXDyn: Dynamics-Informed Species and Reaction Detection Methodology from Atomistic Simulations'
subtitle: ''
summary: ''
authors:
- Raj Maddipati
- Dhruthi Boddapati
- Elangannan Arunan
- Phani Motamarri
- Konduri Aditya
tags: 
- Computational Chemistry
categories: []
date: '2026-06-17'
lastmod: 2026-04-01T15:41:54+05:30
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
publishDate: '2026-04-17T10:11:54.000000Z'
publication_types:
- '3'
abstract: 'Accurate identification of chemical species and reaction pathways from molecular dynamics (MD) trajectories is a prerequisite for deriving predictive chemical kinetic models and for mechanistic discovery in reactive systems. However, state-of-the-art trajectory analysis methods infer bonding from instantaneous distance thresholds, which can misclassify transient, nonreactive encounters as bonds and thereby introduce spurious intermediates, distorted reaction networks, and biased rate estimates. Here, we introduce ChemXDyn, a dynamics-aware computational methodology that leverages time-resolved interatomic distance (IAD) signatures as a core principle to robustly identify chemically consistent bonded interactions and, consequently, extract meaningful reaction pathways. In particular, ChemXDyn propagates molecular connectivity through time while enforcing atomic valence and coordination constraints to distinguish genuine bond-breaking and bond-forming events from transient, nonreactive encounters. We evaluate ChemXDyn on ReaxFF MD simulations of hydrogen and ammonia oxidation and on neural-network potential MD simulations of methane oxidation and benchmark its performance against widely used trajectory analysis methods. Across these cases, ChemXDyn suppresses unphysical species prevalent in static analyses, recovers experimentally consistent reaction pathways, and improves the fidelity of the rate constant estimation. In ammonia oxidation, ChemXDyn removes unphysical intermediates (including N3O, N3O, N4O2, and HN2O2) and resolves key NOx- and N2O-forming and -consuming routes (for example, NH2 + HO2 → H2NO + OH and N2O + H → N2 + OH). In methane oxidation, it reconstructs the canonical progression CH4 → CH3 → CH2 → CH → CHO/CH2O → CO → CO2, which is consistent with established mechanisms yet is often fragmented by threshold-based approaches. By linking atomistic dynamics to chemically consistent reaction identification, ChemXDyn provides a transferable foundation for MD-derived reaction networks and kinetics, with potential utility spanning combustion, heterogeneous catalysis, plasma chemistry, and electrochemical reaction environments.'
publication: 'Journal of Chemical Theory and Computation'
doi: 10.1021/acs.jctc.6c00242
links:
- name: URL
  url: https://doi.org/10.1021/acs.jctc.6c00242
---
