---
citekey: "soLEAPCBFSafetyFilterUncertainSystemsLeastEffort2026"
title: "LEAP-CBF: A Safety Filter for Uncertain Systems with Least-Effort Adversarial Potentials"
authors: ["Oswin So", "Eric Yu", "Chuchu Fan"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.28364"
doi: "10.48550/arXiv.2609.28364"
tags: [paper, embodied-ai, "cs.LG", "cs.RO", "math.OC"]
status: unread
rating:
created: 2026-09-25
---

# LEAP-CBF: A Safety Filter for Uncertain Systems with Least-Effort Adversarial Potentials

> Oswin So, Eric Yu, Chuchu Fan · 2026
> [arXiv](https://arxiv.org/abs/2609.28364) · [PDF](https://arxiv.org/pdf/2609.28364)

## Abstract

Control barrier functions (CBF) are a popular safety filter to ensure safety for nonlinear dynamical systems. However, when the system is subject to uncertainties and disturbances, this requires the use of robust variants of CBFs, which can be difficult to construct and can be overly conservative, especially for high-dimensional systems under input constraints. In this work, we propose a new approach to solve these challenges by introducing Least-Effort Adversarial Potentials (LEAP), a certificate that quantifies the robustness of a given state against disturbances in terms of the effort required by the disturbance to cause failure. We show that LEAP is a CBF for the undisturbed system, but can also be used to construct a safety filter that is robust to disturbances whose cumulative effort is bounded. We propose a method for constructing LEAPs with on-policy deep reinforcement learning. Next, we demonstrate LEAPs in simulation on a variety of multi-agent systems with disturbances and uncertainties. Finally, hardware experiments on a quadruped and quadrotors validate that LEAPs are well suited to tackle the disturbances and uncertainties from real-world robotic systems.

## TL;DR

Control barrier functions (CBF) are a popular safety filter to ensure safety for nonlinear dynamical systems. However, when the system is subject to uncertainties and disturbances, this requires the use of robust variants of CBFs, which can be difficult to construct and can be overly conservative, especially for high-dimensional systems under input constraints.

## Related
<!-- [[other-paper-citekey]] -->
