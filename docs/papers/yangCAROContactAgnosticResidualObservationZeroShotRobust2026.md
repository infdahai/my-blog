---
citekey: "yangCAROContactAgnosticResidualObservationZeroShotRobust2026"
title: "CARO: Contact-Agnostic Residual Observation for Zero-Shot Robust Quadruped Locomotion"
authors: ["Zihan Yang", "Shixuan Han", "Kexin Guo", "Xiang Yu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.24217"
doi: "10.48550/arXiv.2608.24217"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-07
---

# CARO: Contact-Agnostic Residual Observation for Zero-Shot Robust Quadruped Locomotion

> Zihan Yang, Shixuan Han, Kexin Guo, Xiang Yu · 2026
> [arXiv](https://arxiv.org/abs/2608.24217) · [PDF](https://arxiv.org/pdf/2608.24217)

## Abstract

We propose CARO, a contact-agnostic residual observation framework for policy adaptation. CARO embeds a fixed-base Euler--Lagrange model into the reinforcement learning control loop and constructs a torque-level residual observation without requiring torque sensors, explicit contact estimation, or vision-based measurements of the floating-base position and linear velocity. A disturbance observer extracts a structured signal representing dynamics mismatch, while the policy learns to exploit this feedback for online adaptation. CARO is trained under the same terrain, command, and domain-randomization conditions as the nominal policy, without specialized disturbance curricula or additional adaptation supervision. Nevertheless, it achieves substantially improved zero-shot robustness in simulation and sim-to-real transfer tasks involving out-of-distribution payloads, center-of-mass shifts, terrain geometries, abrupt dynamics changes, and elevated-platform landings.

## TL;DR

We propose CARO, a contact-agnostic residual observation framework for policy adaptation. CARO embeds a fixed-base Euler--Lagrange model into the reinforcement learning control loop and constructs a torque-level residual observation without requiring torque sensors, explicit contact estimation, or vision-based measurements of the floating-base position and linear velocity.

## Related
<!-- [[other-paper-citekey]] -->
