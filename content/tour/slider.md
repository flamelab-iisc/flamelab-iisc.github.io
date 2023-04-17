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
      content: 'Staged gas turbines with two sequential combustion chambers are being developed for power generation for their ability to achieve low emissions within a wide operational range while conserving high thermal efficiency. A particular implementation of the sequential combustion concept is characterized by a reheat combustion stage downstream of a first premixed-type combustor. Hot exhaust gases from the first stage are mixed with fuel in a mixing section, which provides the inlet conditions for the second-stage reheat combustor. Direct numerical simulations (DNS) of flame stabilization regimes in the reheat burner, i.e. the combustor including the mixing section (duct-in-a-duct), at idealized conditions are performed using a detailed hydrogen-air mechanism. In particular, this project investigates the role of autoignition in flame stabilization under different stratified conditions of fuel-oxidizer mixture at the inlet. Results from the simulations show that the combustion occurs both due to auto-ignition as well as flame propagation. The auto-ignition mode occurs at and around the centerline of the combustor while flame propagation is stabilized at the recirculation zones near the corners. A typical realization of the flow field is shown in the figure. Chemical explosive mode analysis has been employed to quantify the contribution of auto-ignition to the combustion rate relative to flame propagation. The insights from this project are being used by Ansaldo Energia (a major gas turbine company), for the design their next generation gas turbine combustor.'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: reheat.png
    
    - title: Cavity Stabilized Flames
      content: 'Flame stabilization in scramjet combustors used in hypersonic flight is a challenge. At the relevant flight conditions that result in short residence times of the order of 0.1 ms, flame stabilization is often achieved using a cavity flame holder that recirculates hot products of combustion including radicals. In this study, we use massively parallel direct numerical simulations (DNS) to understand the stabilization of a lean ethylene-air premixed flame in the shear layer above a rectangular cavity and the interactions between the flame and the shear layer vorticity. We found that the flame stabilization is significantly affected by the shear flow dynamics between the main flow and the cavity flow, while the recirculation flow pattern within the cavity is dictated by its aspect ratio. Results also show that the recirculation zone transports necessary hot radicals such as OH from the downstream region to the stabilization point. The vorticity which is present mainly on the reactant side of the flame near the stabilization point, gets advected into the products downstream. This leads to an enhanced heat transfer from the flame to the wall, and affects the CO and OH oxidation. The finding suggests that a better cooling system needs to be provided in the design of a scramjet combustor to prevent thermal damages. The data from these simulations will be used to develop reduced order models necessary for engineering simulations. These insights are applicable to cavity-stabilized configurations for gas turbines as well'
      align: right
      background:
        position: left
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
