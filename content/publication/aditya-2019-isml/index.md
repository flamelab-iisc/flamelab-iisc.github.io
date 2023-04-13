---
title: "Anomaly detection in scientific data using joint statistical moments"
date: 2019-01-01
publishDate: 2020-06-20T20:49:33.535995Z
authors: ["Konduri Aditya", "Hemanth Kolla", "W. Philip Kegelmeyer", "Timothy M. Shead", "Julia Ling", "Warren L. Davis"]
publication_types: ["2"]
abstract: "We propose an anomaly detection method for multi-variate scientific data based on analysis of high-order joint moments. Using kurtosis as a reliable measure of outliers, we suggest that principal kurtosis vectors, by analogy to principal component analysis (PCA) vectors, signify the principal directions along which outliers appear. The inception of an anomaly, then, manifests as a change in the principal values and vectors of kurtosis. Obtaining the principal kurtosis vectors requires decomposing a fourth order joint cumulant tensor for which we use a simple, computationally less expensive approach that involves performing a singular value decomposition (SVD) over the matricized tensor. We demonstrate the efficacy of this approach on synthetic data, and develop an algorithm to identify the occurrence of a spatial and/or temporal anomalous event in scientific phenomena. The algorithm decomposes the data into several spatial sub-domains and time steps to identify regions with such events. Feature moment metrics, based on the alignments of the principal kurtosis vectors, are computed at each sub-domain and time step for all features to quantify their relative importance towards the overall kurtosis in the data. Accordingly, spatial and temporal anomaly metrics for each sub-domain are proposed using the Hellinger distance of the feature moment metric distribution from a suitable nominal distribution. We apply the algorithm to two turbulent auto-ignition combustion cases and demonstrate that the anomaly metrics reliably capture the occurrence of auto-ignition in relevant spatial sub-domains at the right time steps."
featured: false
publication: "*Journal of Computational Physics*"
tags: ["Anomaly detection", "Scientific computing", "Co-kurtosis", "Tensor decomposition", "Hellinger distance", "Auto-ignition"]
url_pdf: "http://www.sciencedirect.com/science/article/pii/S002199911930172X"
doi: "https://doi.org/10.1016/j.jcp.2019.03.003"
share: false
---

