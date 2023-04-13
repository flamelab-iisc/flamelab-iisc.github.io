---
title: "Implementation of low-storage Runge-Kutta time integration schemes in scalable asynchronous partial differential equation solvers"
date: 2023-03-15
publishDate: 2023-03-15T20:49:33.535995Z
authors: ["Shubham K. Goswami", "Vinod J. Matthew", "Konduri Aditya"]
publication_types: ["2"]
abstract: "The asynchronous computing method based on finite-difference schemes has shown promise in significantly improving the scalability of time-dependent partial differential equation (PDE) solvers by either relaxing data synchronization or avoiding communication between processing elements (PEs) on massively parallel machines. This method uses high-order accurate asynchrony-tolerant (AT) schemes coupled with appropriate time integration schemes to provide the desired accuracy required by high-fidelity solvers such as the direct numerical simulations for fluid flow. For time integration, Runge-Kutta (RK) schemes, particularly the low-storage implementation, are widely used due to their ability to provide good stability properties and be computationally efficient. However, the implementation of AT schemes with multi-stage RK schemes necessitates an over-decomposition of the spatial domain in a parallel setting, leading to increased message sizes for communication and redundant computations. In this paper, we propose a novel method to couple asynchrony-tolerant and low-storage explicit RK schemes in solving time-dependent PDEs that would result in a significant reduction in communications and relaxed synchronizations. We develop new asynchrony-tolerant schemes for ghost or buffer point updates that are necessary to maintain desired order of accuracy. The accuracy of this method is investigated, both theoretically and numerically, using simple one-dimensional linear model equations. Thereafter, we demonstrate the scalability of the proposed numerical method through three-dimensional simulations of decaying Burgers' turbulence, performed using two different asynchronous algorithms: communication-avoiding and synchronization-avoiding algorithms. The scalability studies up to 27,000 cores were found to yield speed-ups up to 6× compared to a baseline synchronous algorithm. Overall, the proposed approach shows the potential to improve the scalability of exascale PDE solvers significantly."
featured: false
publication: "*Journal of Computational Physics*"
tags: ["Asynchronous computing", "Partial differntial equations", "Massive computations", "FInite difference schemes", "Runge-Kutta schemes"]
url_pdf: "https://www.sciencedirect.com/science/article/pii/S0021999123000177"
doi: "https://doi.org/10.1016/j.jcp.2023.111922"
share: false
---

