---
widget: slider
headless: true
weight: 1
active: true

design:
  slide_height: '300px'
  is_fullscreen: false
  loop: true
  interval: 4000

content:
  slides:
    - title: Gas Turbine Engine Combustion
      content: 'Direct numerical simulations of flame stabilization in reheat combustors, investigating autoignition and flame propagation roles under stratified fuel-oxidizer conditions.'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: reheat.png

    - title: Cavity Stabilized Flames
      content: 'Massively parallel DNS to understand flame stabilization in scramjet combustors, revealing shear flow dynamics and radical transport from cavity recirculation zones.'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: scramjet.png

    - title: Reactive Molecular Dynamics
      content: 'Chemical kinetic modeling of hydrogen-oxygen systems using ReaxFF and ab-initio MD to extract complete reaction mechanisms and rate constants at extreme conditions.'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: rmd.png

    - title: Asynchronous Numerical Schemes
      content: 'Asynchrony-tolerant schemes for massively parallel CFD that relax synchronization between processing elements, improving scalability on Exascale machines.'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.4
        media: async.png

    - title: Super-Resolution of Turbulent Fields
      content: 'Physics-guided generative adversarial networks to reconstruct small-scale turbulent structures from large-scale data, without high-resolution reference data for training.'
      align: right
      background:
        position: center
        color: '#555'
        brightness: 0.5
        media: sres.png

    - title: Detection of Extreme Events
      content: 'Anomaly detection method using higher-order statistical moments to identify extreme events, applied to autoignition kernels in turbulent combustion and intermittent turbulence.'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: anomaly.png
---
