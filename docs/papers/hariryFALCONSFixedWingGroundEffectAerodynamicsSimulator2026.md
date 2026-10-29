---
citekey: "hariryFALCONSFixedWingGroundEffectAerodynamicsSimulator2026"
title: "FALCON-S: Fixed-wing ground-effect Aerodynamics Simulator and Flight Control Learning Suite"
authors: ["Matteo El Hariry", "Pedro Lima", "Andrej Orsula", "Matthieu Geist", "Miguel Olivares-Mendez"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.06046"
doi: "10.48550/arXiv.2609.06046"
tags: [paper, embodied-ai, "cs.LG", "cs.RO", "eess.SY"]
status: unread
rating:
created: 2026-09-11
---

# FALCON-S: Fixed-wing ground-effect Aerodynamics Simulator and Flight Control Learning Suite

> Matteo El Hariry, Pedro Lima, Andrej Orsula, Matthieu Geist, Miguel Olivares-Mendez · 2026
> [arXiv](https://arxiv.org/abs/2609.06046) · [PDF](https://arxiv.org/pdf/2609.06046)

## Abstract

We present a modular, high-fidelity simulation framework for the development and benchmarking of flight control strategies in fixed-wing aerial robots operating near the ground. Unlike existing simulators that rely on simplified or hover-oriented dynamics, our framework models full 6DoF rigid-body physics, semi-empirical ground-effect aerodynamics, actuator dynamics, sensor noise, and environmental disturbances. This physical realism, combined with modular component design, enables systematic analysis of low-altitude flight behavior under realistic conditions. The simulator supports both CPU and GPU backends via Torch and NVIDIA Warp, enabling high-throughput parallel execution suitable for large-scale reinforcement learning training and optimal control rollouts. A unified interface accommodates a range of controllers (both RL and optical control algorithms) across tasks such as altitude regulation and trajectory tracking. Cross-validation with X-Plane and JSBSim is also supported to facilitate engineering integration and visual fidelity.

## TL;DR

We present a modular, high-fidelity simulation framework for the development and benchmarking of flight control strategies in fixed-wing aerial robots operating near the ground. Unlike existing simulators that rely on simplified or hover-oriented dynamics, our framework models full 6DoF rigid-body physics, semi-empirical ground-effect aerodynamics, actuator dynamics, sensor noise, and environmental disturbances.

## Related
<!-- [[other-paper-citekey]] -->
