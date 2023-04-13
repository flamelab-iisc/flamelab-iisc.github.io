---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: 👋 Welcome to the group
      content: Take a look at what we're working on...
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: slider-front.JPG
    
    - title: Gas Turbine Engine Combustion
      content: 'Investigation of turbulent combustion phenomena in stationary gas turbine engines using massively-parallel direct numerical simulations.'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: reheat.png
    
    - title: Cavity Stabilized Flames
      content: 'Investigation of turbulent combustion phenomena in cavity stabilized flames relevant to gas turbines and scramjets using large scale direct numerical simulations.'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: scramjet.png

    - title: Reactive Molecular Dynamics
      content: 'Development of a multiscale framework that combines atomistic simulations to analyze the chemical kinetics of fuel and then use this information in continuum scale simulations of reacting flow. The proposed framework would establish a chemical genome that could be employed to rapidly simulate various types of new chemical systems.'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: rmd.png

    - title: Asynchronous Numerical Schemes
      content: 'Development of asynchronous numerical schemes for massively parallel PDE solvers and investigation of their numerical and scaling properties compared to standard synchronous schemes'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.4
        media: async.png

    - title: Super-resolution of turbulent fields
      content: 'Development of generative machine learning techniques for the reconstruction of intricate details in turbulent fields.'
      align: right
      background:
        position: center
        color: '#555'
        brightness: 0.5
        media: sres.png
    - title: Detection of Extreme Events
      content: 'Development of machine learning methods for the detection of anomalous or extreme events in scientific phenomena.'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: anomaly.png
      
---
