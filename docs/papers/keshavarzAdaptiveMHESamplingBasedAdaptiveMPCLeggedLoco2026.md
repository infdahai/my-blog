---
citekey: "keshavarzAdaptiveMHESamplingBasedAdaptiveMPCLeggedLoco2026"
title: "Adaptive-MHE : A Sampling-Based Adaptive MPC for Legged Loco-Manipulation via Moving Horizon Estimation"
authors: ["Hossein Keshavarz", "Alejandro Ramirez-Serrano", "Majid Khadiv"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.17832"
doi: "10.48550/arXiv.2609.17832"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-17
---

# Adaptive-MHE : A Sampling-Based Adaptive MPC for Legged Loco-Manipulation via Moving Horizon Estimation

> Hossein Keshavarz, Alejandro Ramirez-Serrano, Majid Khadiv · 2026
> [arXiv](https://arxiv.org/abs/2609.17832) · [PDF](https://arxiv.org/pdf/2609.17832)

## Abstract

Legged robots have demonstrated a remarkable ability to traverse various terrains, yet generating effective loco-manipulation behaviors remains challenging. A key difficulty is that object and terrain parameters are typically unknown to the robot, and mismatches between these parameters and their simulated counterparts introduce a sim-to-real gap that degrades control performance. Classical system identification (Sys-ID) methods often assume differentiable dynamics, an assumption that does not hold for contact-rich legged systems. Sampling-based Sys-ID avoids this restriction by directly matching simulated and recorded state trajectories through massively parallel rollouts, but existing approaches are typically applied offline and do not adapt as environmental conditions change. We present Adaptive-MHE an online sampling-based Sys-ID framework, based on moving horizon estimation (MHE), that estimates the physical parameters of objects and terrain in the environment (e.g., mass, friction) and couples this estimate with a sampling-based model predictive controller, enabling adaptive loco-manipulation in changing and uncertain environments. In simulation and hardware experiments, our framework consistently outperforms baselines and matches the performance of a controller with access to ground-truth parameters.

## TL;DR

Legged robots have demonstrated a remarkable ability to traverse various terrains, yet generating effective loco-manipulation behaviors remains challenging. A key difficulty is that object and terrain parameters are typically unknown to the robot, and mismatches between these parameters and their simulated counterparts introduce a sim-to-real gap that degrades control performance.

## Related
<!-- [[other-paper-citekey]] -->
