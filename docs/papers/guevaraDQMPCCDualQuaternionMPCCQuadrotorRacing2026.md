---
citekey: "guevaraDQMPCCDualQuaternionMPCCQuadrotorRacing2026"
title: "DQ-MPCC: Dual-Quaternion MPCC for Quadrotor Racing"
authors: ["Bryan S. Guevara", "Luis F. Recalde", "Guanrui Li", "Tiago Nascimento"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.36482"
doi: "10.48550/arXiv.2609.36482"
tags: [paper, embodied-ai, "cs.RO", "eess.SY"]
status: unread
rating:
created: 2026-09-30
---

# DQ-MPCC: Dual-Quaternion MPCC for Quadrotor Racing

> Bryan S. Guevara, Luis F. Recalde, Guanrui Li, Tiago Nascimento · 2026
> [arXiv](https://arxiv.org/abs/2609.36482) · [PDF](https://arxiv.org/pdf/2609.36482)

## Abstract

Quadrotor racing demands aggressive attitude and progress control while passing through every gate, and conventional quadrotor MPCC formulations state the prediction model in inertial coordinates and the attitude error in the body frame. We present a Dual-Quaternion Model Predictive Contouring Control (DQ-MPCC) for quadrotor racing in which the pose is a unit dual quaternion and the contouring errors are projected onto the tangent space of the dual quaternion manifold, expressed in the desired body frame: the same rigid-body dynamics as the conventional model, in unified pose-twist coordinates in the body frame. We compare DQ-MPCC against a baseline MPCC through Monte Carlo software-in-the-loop simulations and real-world racing on an eight-gate circuit of 11x4.5x3.65 m. With the same gains in simulation and hardware, DQ-MPCC keeps every crossing of its completed flights within the prescribed geometric margin, whereas the baseline exceeds it, its median worst-gate offset growing by 71.5% sim-to-real against a 10.1% decrease for DQ-MPCC. Among the configurations that keep every simulated gate crossing within the geometric margin, DQ-MPCC also reduces the minimum lap time by 6.7%, and by 10.5% in the real-world flights, while running onboard at 100 Hz.

## TL;DR

Quadrotor racing demands aggressive attitude and progress control while passing through every gate, and conventional quadrotor MPCC formulations state the prediction model in inertial coordinates and the attitude error in the body frame. We present a Dual-Quaternion Model Predictive Contouring Control (DQ-MPCC) for quadrotor racing in which the pose is a unit dual quaternion and the contouring errors are projected onto the tangent space of the dual quaternion manifold, expressed in the desired body frame: the same rigid-body dynamics as the conventional model, in unified pose-twist...

## Related
<!-- [[other-paper-citekey]] -->
