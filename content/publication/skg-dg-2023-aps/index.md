---
title: "Implementation of the asynchronous discontinuous-Galerkin method for reacting flow simulations"
date: 2023-11-19
publishDate: 2023-11-19T20:49:33.542875Z
authors: ["Shubham K. Goswami", "Dapse Vidyesh", "Konduri Aditya"]
publication_types: ["1"]
abstract: "One of the recent advancements toward the development of asynchronous numerical schemes for scalable PDE solvers is the newly introduced asynchronous discontinuous-Galerkin (ADG) method. It avoids communication/synchronization at a mathematical level and uses asynchrony-tolerant (AT) fluxes to provide highly accurate solutions despite asynchrony. The ADG method is particularly beneficial for massively parallel reacting flow solvers, where the chemical time scale is very small, such that simulation time is extremely long. These simulations are typically performed on tens of thousands of processors, where communication overheads significantly affect the scalability of the solver. In this work, we implement the ADG method in a 1D solver, aimed at solving compressible Navier-Stokes equations with relaxed communication/synchronization requirements. A series of numerical experiments are performed to validate its performance for reacting and non-reacting problems. We also demonstrate the scalability of the ADG method based on one of the compressible flow solvers in deal. II (an open-source finite element library) for two and three-dimensional inviscid flow problems. The results demonstrate the great potential of the ADG method for developing exascale PDE solvers for reacting flow simulations."
featured: false
publication: "*2023 Bulletin of the American Physical Society*"
doi: ""
tags: ["asyncdg"]
share: false
---

