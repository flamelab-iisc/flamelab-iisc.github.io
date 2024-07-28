---
title: "An asynchronous discontinuous Galerkin method for massively parallel PDE solvers"
date: 2024-10-01
publishDate: 2024-10-01T20:49:33.542875Z
authors: ["Shubham K. Goswami", "Konduri Aditya"]
publication_types: ["1"]
abstract: "The discontinuous Galerkin (DG) method is widely being used to solve hyperbolic partial differential equations (PDEs) due to its ability to provide high-order accurate solutions in complex geometries, capture discontinuities, and exhibit high arithmetic intensity. However, the scalability of DG-based solvers is impeded by communication bottlenecks arising from the data movement and synchronization requirements at extreme scales. To address these challenges, recent studies have focused on the development of asynchronous computing approaches for PDE solvers. Herein, we introduce the asynchronous DG (ADG) method, which combines the benefits of the DG method with asynchronous computing to overcome communication bottlenecks. The ADG method relaxes the need for data communication and synchronization at a mathematical level, allowing processing elements to operate independently regardless of the communication status, thus potentially improving the scalability of solvers. The proposed ADG method ensures flux conservation and effectively addresses challenges arising from asynchrony. To assess its stability, Fourier-mode analysis is employed to examine the dissipation and dispersion behavior of fully-discrete equations that use the DG and ADG schemes along with the Runge–Kutta (RK) time integration scheme. Furthermore, an error analysis within a statistical framework is presented, which demonstrates that the ADG method with standard numerical fluxes achieves at most first-order accuracy. To recover accuracy, we introduce asynchrony-tolerant (AT) fluxes that utilize data from multiple time levels. Extensive numerical experiments were conducted to validate the performance of the ADG-AT scheme for both linear and nonlinear problems. Overall, the proposed ADG-AT method demonstrates the potential to achieve accurate and scalable DG-based PDE solvers, paving the way for simulations of complex physical systems on massively parallel supercomputers."
featured: false
publication: "*Computer Methods in Applied Mechanics and Engineering*"
doi: "https://doi.org/10.1016/j.cma.2024.117218"
url_pdf: "https://www.sciencedirect.com/science/article/pii/S0045782524004742"
tags: ["asyncdg"]
share: false
---

