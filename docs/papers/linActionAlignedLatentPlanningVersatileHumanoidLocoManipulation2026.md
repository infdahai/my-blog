---
citekey: "linActionAlignedLatentPlanningVersatileHumanoidLocoManipulation2026"
title: "Action-Aligned Latent Planning for Versatile Humanoid Loco-Manipulation"
authors: ["Yutang Lin", "Guanya Shi", "C. Karen Liu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.24675"
doi: "10.48550/arXiv.2610.24675"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-22
---

# Action-Aligned Latent Planning for Versatile Humanoid Loco-Manipulation

> Yutang Lin, Guanya Shi, C. Karen Liu · 2026
> [arXiv](https://arxiv.org/abs/2610.24675) · [PDF](https://arxiv.org/pdf/2610.24675)

## Abstract

Learning a single perceptive policy for diverse humanoid loco-manipulation requires unifying high-level task decisions without losing the state-dependent physical responses that make each interaction succeed. This makes the representation between high-level planning and whole-body control critical: kinematic or contact targets provide compact abstractions but do not directly encode interaction-specific control responses, while directly predicting low-level actions requires the planner to model high-frequency closed-loop feedback. We propose FIBER, a framework that uses the executable latent space of a frozen behavioral foundation model (BFM) as a shared planning representation for heterogeneous interaction skills. Our latent policy projection (LPP) maps independently acquired task-specific policies into this representation by identifying latent commands whose induced actions match their local control responses, enabling lower-rate planning while retaining the BFM's high-frequency state feedback. After projection, we aggregate closed-loop latent rollouts from all skills and train a single perceptive flow planner entirely offline. We further introduce AH-BFM, an adaptive-horizon BFM trained with multi-gamma forward-backward (FB) learning to support both precise control and temporally extended whole-body behavior. We evaluate FIBER on box pickup, door opening, and object grasping in simulation and on a real Unitree G1 humanoid. Across 128 diverse variations per task in simulation, FIBER achieves 42.0% mean success, more than tripling projected latent replay (11.6%) and substantially outperforming kinematic planning (3.5%). Real-world experiments further demonstrate sim-to-real transfer, skill chaining, and conditional steering through the same unified planner.

## TL;DR

Learning a single perceptive policy for diverse humanoid loco-manipulation requires unifying high-level task decisions without losing the state-dependent physical responses that make each interaction succeed. This makes the representation between high-level planning and whole-body control critical: kinematic or contact targets provide compact abstractions but do not directly encode interaction-specific control responses, while directly predicting low-level actions requires the planner to model high-frequency closed-loop feedback.

## Related
<!-- [[other-paper-citekey]] -->
