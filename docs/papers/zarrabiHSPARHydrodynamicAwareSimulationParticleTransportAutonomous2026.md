---
citekey: "zarrabiHSPARHydrodynamicAwareSimulationParticleTransportAutonomous2026"
title: "H-SPAR: Hydrodynamic-aware Simulation for Particle Transport and Autonomous Robots"
authors: ["Navid Zarrabi", "Nariman Yousefi", "Sajad Saeedi"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.01985"
doi: "10.48550/arXiv.2610.01985"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-04
---

# H-SPAR: Hydrodynamic-aware Simulation for Particle Transport and Autonomous Robots

> Navid Zarrabi, Nariman Yousefi, Sajad Saeedi · 2026
> [arXiv](https://arxiv.org/abs/2610.01985) · [PDF](https://arxiv.org/pdf/2610.01985)

## Abstract

Environmental robotic sampling requires considering the dual influence of water currents on robotic motion and particle transport. Existing marine robotics simulators generally model flow, autonomy, and sampling targets separately, limiting joint evaluation of mission cost and sampling performance. H-SPAR integrates spatially and temporally varying velocity fields, Lagrangian particle transport, probabilistic sampling, and ROS 2/Gazebo-based uncrewed surface vehicle (USV) autonomy. In this work, shared precomputed flow fields drive particle advection and current-induced forces during closed-loop vehicle execution. Path-planning experiments show that the existing current-aware planner SVF-RRT* achieves 69.4% lower upstream cost than conventional RRT* at the planning level, but this reduction falls to 41.7% during execution under time-varying currents, reflecting temporal flow variation, vehicle motion constraints, and path deviation omitted during planning. Coverage experiments show that sweep orientation changes the particle-sampling rate by up to 22.2% under the complete H-SPAR configuration. These findings highlight the importance of evaluating planning, vehicle execution, particle transport, and sampling together under consistent hydrodynamic conditions. The project webpage is available at https://sites.google.com/view/h-spar, and the open-source code is available on GitHub at https://github.com/naviiidz/h-spar-sim.

## TL;DR

Environmental robotic sampling requires considering the dual influence of water currents on robotic motion and particle transport. Existing marine robotics simulators generally model flow, autonomy, and sampling targets separately, limiting joint evaluation of mission cost and sampling performance.

## Related
<!-- [[other-paper-citekey]] -->
