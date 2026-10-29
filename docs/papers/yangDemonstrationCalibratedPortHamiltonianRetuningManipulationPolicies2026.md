---
citekey: "yangDemonstrationCalibratedPortHamiltonianRetuningManipulationPolicies2026"
title: "Demonstration-Calibrated Port-Hamiltonian Retuning for Manipulation Policies"
authors: ["Yulong Yang", "Fan Wu", "Christine Allen-Blanchette", "Amit Chakraborty"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.05755"
doi: "10.48550/arXiv.2610.05755"
tags: [paper, embodied-ai, "cs.RO", "eess.SY"]
status: unread
rating:
created: 2026-10-07
---

# Demonstration-Calibrated Port-Hamiltonian Retuning for Manipulation Policies

> Yulong Yang, Fan Wu, Christine Allen-Blanchette, Amit Chakraborty · 2026
> [arXiv](https://arxiv.org/abs/2610.05755) · [PDF](https://arxiv.org/pdf/2610.05755)

## Abstract

Diffusion and VLA policies for manipulation are often deployed through downstream impedance controllers. The stiffness and damping gains of these controllers affect task success, yet are commonly inherited from data collection rather than selected for the deployed policy. Although empirical gain sweeps can improve performance, they require repeated evaluation rollouts. We introduce PHRetune, an offline method that derives controller gains for a frozen policy without evaluation rollouts or gain search. Our approach learns a port-Hamiltonian model from demonstrations to estimate the effort and energy associated with the policy's predicted actions. The policy is applied to recorded demonstration observations, and its predictions are assessed against demonstration-derived effort and energy budgets. From this comparison, we derive a single gain scale in closed form, adjusting the downstream controller while preserving the policy and its action representation. The gains are fixed before evaluation, without requiring a prior manipulator model, task rewards, policy retraining, or additional runtime computation. Across LIBERO suites, PHRetune improves Diffusion Policy success by up to 9.4 percentage points, with the derived gains achieving the highest observed success rates in empirical gain sweeps. On all four real-world manipulation tasks, PHRetuned Diffusion Policy outperforms the nominal policy, alternative gain-tuning methods, and a policy-retraining baseline. The same procedure improves success with SmolVLA and OpenVLA-OFT on every task, while reducing acceleration and jerk for both VLA backbones.

## TL;DR

Diffusion and VLA policies for manipulation are often deployed through downstream impedance controllers. The stiffness and damping gains of these controllers affect task success, yet are commonly inherited from data collection rather than selected for the deployed policy.

## Related
<!-- [[other-paper-citekey]] -->
