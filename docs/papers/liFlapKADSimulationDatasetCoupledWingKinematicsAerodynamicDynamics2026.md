---
citekey: "liFlapKADSimulationDatasetCoupledWingKinematicsAerodynamicDynamics2026"
title: "FlapKAD: A Simulation Dataset of Coupled Wing Kinematics and Aerodynamic Dynamics for Flapping-Wing Aerial Vehicles"
authors: ["Haichuan Li"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.38719"
doi: "10.48550/arXiv.2609.38719"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-04
---

# FlapKAD: A Simulation Dataset of Coupled Wing Kinematics and Aerodynamic Dynamics for Flapping-Wing Aerial Vehicles

> Haichuan Li · 2026
> [arXiv](https://arxiv.org/abs/2609.38719) · [PDF](https://arxiv.org/pdf/2609.38719)

## Abstract

Experimental investigation and modeling of flapping-wing aerial vehicles are limited by the scarcity of large-scale records that temporally align wing kinematics, aerodynamic responses, and flight states. Existing datasets are often limited in scale and affected by measurement noise and temporal misalignment between rapidly varying wing motion and the associated dynamic response, particularly during high-frequency flapping. We introduce FlapKAD, an episode-structured simulation dataset comprising 2,000 rigid-wing flight episodes and 720,152 valid time steps, with bilateral wing kinematics, aerodynamic responses, and flight states recorded synchronously within a common clock. FlapKAD supports a unified bidirectional sequence-prediction benchmark constructed from the same temporally aligned episodes. The forward task predicts future vertical force coefficients and body vertical velocity from histories of realized flap and twist angles, whereas the inverse task reconstructs future flap- and twist-angle trajectories from the corresponding response histories. A benchmark of eight representative time-series architectures across multiple prediction horizons reveals direction- and horizon-dependent model behavior, systematically higher reconstruction errors for twist angle than for flap angle, and no consistent advantage from increased architectural complexity. FlapKAD provides a reproducible dataset and benchmark for studying coupled wing-kinematic, aerodynamic, and flight-state dynamics in flapping-wing aerial vehicles.

## TL;DR

Experimental investigation and modeling of flapping-wing aerial vehicles are limited by the scarcity of large-scale records that temporally align wing kinematics, aerodynamic responses, and flight states. Existing datasets are often limited in scale and affected by measurement noise and temporal misalignment between rapidly varying wing motion and the associated dynamic response, particularly during high-frequency flapping.

## Related
<!-- [[other-paper-citekey]] -->
