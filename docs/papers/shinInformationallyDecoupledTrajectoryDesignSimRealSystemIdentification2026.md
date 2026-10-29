---
citekey: "shinInformationallyDecoupledTrajectoryDesignSimRealSystemIdentification2026"
title: "Informationally Decoupled Trajectory Design for Sim-to-Real System Identification"
authors: ["Sangwoo Shin", "Ashvin Anilkumar", "Ryan Gao", "Josiah P. Hanna"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.10905"
doi: "10.48550/arXiv.2610.10905"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-09
---

# Informationally Decoupled Trajectory Design for Sim-to-Real System Identification

> Sangwoo Shin, Ashvin Anilkumar, Ryan Gao, Josiah P. Hanna · 2026
> [arXiv](https://arxiv.org/abs/2610.10905) · [PDF](https://arxiv.org/pdf/2610.10905)

## Abstract

Sampling-based system identification estimates physically meaningful parameters by tuning a simulator to reproduce the target system dynamics, providing an interpretable approach to improving sim-to-real transfer. Yet when the collected trajectories do not distinguish the effects of different parameters, multiple parameter combinations can reproduce those trajectories, leading to unreliable parameter estimates. To address this challenge, we introduce an Informationally Decoupled Trajectory Design framework (IDTD), which formulates the objective for the exploration policy built on the Schur complement score derived from the Fisher information matrix. To faithfully reflect parameter separability in the exploration objective, IDTD normalizes the score against the per-parameter information, selects the most favorable trajectory segment for each parameter, and aggregates the resulting scores logarithmically. The optimized trajectory is therefore composed of complementary intervals, each exposing a distinct subset of parameters whose contribution to the motion over that interval can be attributed unambiguously. Across diverse simulation environments, ranging from a linear-dynamics system to the Go2 quadruped, G1 humanoid, and Crazyflie quadrotor, IDTD reduces the parameter identification error by 39.6% on average relative to the strongest prior active-exploration baseline and attains improved downstream policy transfer. Furthermore, we validate the proposed trajectory design on a real K1 humanoid, demonstrating that the resulting identified parameters accurately capture the real-system dynamics.

## TL;DR

Sampling-based system identification estimates physically meaningful parameters by tuning a simulator to reproduce the target system dynamics, providing an interpretable approach to improving sim-to-real transfer. Yet when the collected trajectories do not distinguish the effects of different parameters, multiple parameter combinations can reproduce those trajectories, leading to unreliable parameter estimates.

## Related
<!-- [[other-paper-citekey]] -->
