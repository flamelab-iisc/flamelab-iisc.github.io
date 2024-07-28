---
title: Super-resolution of Turbulent Fields
date: ''
share: false
show_date: false
---

Deep learning has been extensively used for modeling and analyzing fluid turbulence. One such application is the use of super-resolution (SR) algorithms to reconstruct small-scale structures from large-scale ones for turbulent flows. However, current SR algorithms require high-resolution reference data for training, which is not practical for most fluid flow scenarios. To address this issue, a physics-guided model has been developed using generative adversarial networks to reconstruct small-scale structures relevant to homogeneous isotropic turbulence. The quality of the reconstruction was assessed using spectra, structure functions, and probability density functions of velocity components and a passive scalar. The results showed that the outputs were in statistical agreement with the ground truth, which was excluded from the training, and that the trained network generalized well across Reynolds numbers. This work lays the foundation for reconstructing small-scale structures from large-eddy simulation data without the need for high-resolution reference data.