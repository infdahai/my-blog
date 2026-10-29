---
citekey: "palOneDiffusionModelTwoRolesGuidedTrajectoryPlanning2026"
title: "One Diffusion Model, Two Roles: Guided Trajectory Planning and Safety-Critical Scenario Generation in Closed-Loop Simulation"
authors: ["Arka Pal", "Rajesh Kumar", "Hannes Eriksson", "Rémi Lacombe", "Arvid Laveno Ling", "Ankit Gupta", "Maciej Wozniak"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.04921"
doi: "10.48550/arXiv.2609.04921"
tags: [paper, embodied-ai, "cs.AI", "cs.CV", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-09-07
---

# One Diffusion Model, Two Roles: Guided Trajectory Planning and Safety-Critical Scenario Generation in Closed-Loop Simulation

> Arka Pal, Rajesh Kumar, Hannes Eriksson, Rémi Lacombe, Arvid Laveno Ling, Ankit Gupta, Maciej Wozniak · 2026
> [arXiv](https://arxiv.org/abs/2609.04921) · [PDF](https://arxiv.org/pdf/2609.04921)

## Abstract

Diffusion probabilistic models can capture the multi-modal, interaction-rich distribution of joint future trajectories in driving scenes. We show that a single pretrained diffusion traffic model can serve two complementary roles in the autonomous driving development loop: as an ego motion planner, and as a controllable generator of safety-critical scenarios for stress-testing the planners. On the planning side, we introduce a Single-Stream Dual-Stream (SSDS) diffusion-transformer decoder that fuses scene context via joint attention rather than late cross-attention, improving closed-loop performance on nuPlan. We further propose Decoupled Annealing Posterior Sampling with Energy (DAPSE), a training-free guidance scheme that injects arbitrary energy functions at the clean-sample level, avoiding the first-order approximation errors while requiring no auxiliary networks. Beyond planning, we leverage the same diffusion model as a controllable scenario generator to create realistic long-tail driving interactions for closed-loop evaluation. Through inference-time guidance, selected agents are steered toward safety-critical behaviors, including aggressive cut-ins, lead-vehicle braking, and combined longitudinal-lateral interactions, while preserving realistic traffic behaviors. Evaluated in closed-loop nuPlan simulations with independent black-box planners, the generated scenarios expose failure modes that remain hidden under standard benchmarks. Although the SSDS-based planner achieves stronger nominal performance, it experiences larger degradation under these challenging scenarios, demonstrating that benchmark superiority does not necessarily translate to robustness. These results demonstrate that a single learned traffic prior can simultaneously improve motion planning and provide a realistic framework for systematic planner robustness evaluation.

## TL;DR

Diffusion probabilistic models can capture the multi-modal, interaction-rich distribution of joint future trajectories in driving scenes. We show that a single pretrained diffusion traffic model can serve two complementary roles in the autonomous driving development loop: as an ego motion planner, and as a controllable generator of safety-critical scenarios for stress-testing the planners.

## Related
<!-- [[other-paper-citekey]] -->
