---
citekey: "tommaselliMindPhaseEffectiveRankRepresentationHealthLeggedLocomotion2026"
title: "Mind the Phase: Effective Rank and Representation Health in Legged Locomotion"
authors: ["Felipe Tommaselli", "Thiago H. Segreto", "Juliano D. Negri", "Ricardo V. Godoy", "Marcelo Becker"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.06958"
doi: "10.48550/arXiv.2609.06958"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-09-11
---

# Mind the Phase: Effective Rank and Representation Health in Legged Locomotion

> Felipe Tommaselli, Thiago H. Segreto, Juliano D. Negri, Ricardo V. Godoy, Marcelo Becker · 2026
> [arXiv](https://arxiv.org/abs/2609.06958) · [PDF](https://arxiv.org/pdf/2609.06958)

## Abstract

Reinforcement learning has become the leading paradigm in legged locomotion, enabling complex behaviors from backflips to parkour through massively parallel simulation. Under PPO's non-stationarity, shallow networks remain the de facto architecture, supported by carefully staged curricula and environments, yet the representations these policies learn stay poorly understood, leaving no training-time signal of how they will behave on hardware. In this work, we empirically study locomotion policies through the effective rank of the policy Jacobian and show that conditioning rank on the gait phase exposes architectural structure that global rank averages away. In particular, we find that standard architectural choices, namely layer normalization and residual connections, allocate roughly two more dimensions of effective rank to swing than to stance, which is fully absent in vanilla MLPs. Building on this, we propose a simple recipe that turns these representational signatures into smoother, more reliable sim-to-real transfer. In practice, this results in roughly 3x lower joint jitter that holds from simulation onto a physical Spot, suggesting that representation health is an effective training-time lens to track sim-to-real smoothness.

## TL;DR

Reinforcement learning has become the leading paradigm in legged locomotion, enabling complex behaviors from backflips to parkour through massively parallel simulation. Under PPO's non-stationarity, shallow networks remain the de facto architecture, supported by carefully staged curricula and environments, yet the representations these policies learn stay poorly understood, leaving no training-time signal of how they will behave on hardware.

## Related
<!-- [[other-paper-citekey]] -->
