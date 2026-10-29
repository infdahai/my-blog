---
citekey: "haoDeRiskingWeldingSpaceMetalJoiningThroughPhysics2026"
title: "De-Risking Robotic Welding for In-Space Metal Joining Through Physics-Grounded Digital Twins"
authors: ["Zhou Daniel Hao", "Umer Masood Chaudry", "Robert Shaw", "Andrew Cheney", "Nick Ludford", "Mark Sims", "Hongbiao Dong"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.21939"
doi: "10.48550/arXiv.2610.21939"
tags: [paper, embodied-ai, "cs.RO", "physics.app-ph"]
status: unread
rating:
created: 2026-10-18
---

# De-Risking Robotic Welding for In-Space Metal Joining Through Physics-Grounded Digital Twins

> Zhou Daniel Hao, Umer Masood Chaudry, Robert Shaw, Andrew Cheney, Nick Ludford, Mark Sims, Hongbiao Dong · 2026
> [arXiv](https://arxiv.org/abs/2610.21939) · [PDF](https://arxiv.org/pdf/2610.21939)

## Abstract

Growing interest in in-space servicing, manufacturing, and assembly has renewed attention on reliable metal joining for modular construction and on-orbit repair. Robotic welding is promising, but reduced-gravity and low-pressure operation remains poorly characterised and flight-like tests are limited. The UK Space Agency-supported ISPARK project is developing a physics-grounded digital twin for structured process de-risking. This paper evaluates a model-based prototype combining a finite-volume thermal weld-pool model, Gaussian-process (GP) and neural-network surrogates, and a simulated six-axis manipulator. The reduced model includes solid-liquid phase change, effective thermocapillary transport, and a local-pressure parameter. Gravity is assessed separately through a hydrostatic-to-capillary pressure ratio and does not enter the thermal energy equation. Across repeated five-fold cross-validation, the GP has lower normalised mean absolute error than the neural network for all eight outputs. In 10 held-out boundary cases, 74 of 80 solver responses fall within nominal 90% GP predictive intervals. A three-output GP query takes 249 microseconds, including scaling and predictive variance. In a simulated UR5 L-shaped-seam study, a proportional controller adjusts the synergic power-source setting as travel speed falls near the corner. Finite-volume re-evaluation finds all 12 closed-loop operating points and 9 of 12 open-loop points within an illustrative 1.0-3.0 mm root-side-width band. These simulation results support using the framework to screen welding conditions and control strategies before experimental tests. Thermal-vacuum, targeted reduced-gravity, and robotic hardware-in-the-loop studies are needed to assess the model and controller.

## TL;DR

Growing interest in in-space servicing, manufacturing, and assembly has renewed attention on reliable metal joining for modular construction and on-orbit repair. Robotic welding is promising, but reduced-gravity and low-pressure operation remains poorly characterised and flight-like tests are limited.

## Related
<!-- [[other-paper-citekey]] -->
