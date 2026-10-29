---
citekey: "wangEgoDynamicsAugmentedWorldModelAutonomousDrivingZero2026"
title: "Ego-Dynamics-Augmented World Model for Autonomous Driving with Zero-Shot Cross-Embodiment Adaptation"
authors: ["Zhidong Wang", "Jingsong Liang", "Zirui Li", "Zhan Chen", "Han Yu", "Chen Lv"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2607.13410"
doi: "10.48550/arXiv.2607.13410"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-15
---

# Ego-Dynamics-Augmented World Model for Autonomous Driving with Zero-Shot Cross-Embodiment Adaptation

> Zhidong Wang, Jingsong Liang, Zirui Li, Zhan Chen, Han Yu, Chen Lv · 2026
> [arXiv](https://arxiv.org/abs/2607.13410) · [PDF](https://arxiv.org/pdf/2607.13410)

## Abstract

End-to-end autonomous driving requires generalization ability across platforms with dissimilar physical characteristics. The chassis defines the physical embodiment of each platform, and real-world fleets span sub-tonne microcars to bus-class vehicles. Consequently, the driving stack must either be retrained per platform or adapt to the underlying chassis dynamics online. World model (WM)-based reinforcement learning offers a sample-efficient path toward end-to-end autonomous driving on egocentric bird's-eye-view (BEV) representations, but its effectiveness hinges on how faithfully the WM captures the ego vehicle's dynamics. This work identifies a structural bottleneck in BEV-based WMs: observation transitions entangle ego-motion with scene dynamics, consuming modeling capacity at the cost of imagination accuracy. This burden is embodiment-dependent: dissimilar chassis produce different observation warps under the same control input. The proposed DynaDreamer addresses this bottleneck by conditioning the WM's latent distributions on a physics-informed ego-dynamics context derived from a lateral dynamics model with a neural tire force formulation. This context is extracted online via a neural-ODE encoder-decoder that simultaneously identifies the underlying chassis parameters. Information-theoretic analysis confirms that this conditioning removes the ego-motion terms from both the WM's transition entropy and its prior-posterior KL divergence. The identified physical parameterization enables zero-shot cross-embodiment adaptation across a dynamically diverse fleet without per-platform retraining. Simulation results show 28% and 43% improvements in driving task success rates over the strongest baseline in urban and highway scenarios, and the advantage over the base Transformer WM reaches up to 73% when extrapolating to unseen chassis.

## TL;DR

End-to-end autonomous driving requires generalization ability across platforms with dissimilar physical characteristics. The chassis defines the physical embodiment of each platform, and real-world fleets span sub-tonne microcars to bus-class vehicles.

## Related
<!-- [[other-paper-citekey]] -->
