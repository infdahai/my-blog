---
citekey: "maActSafeGuardDifferentiableTrainingAlignedConstraintEnforcementFlowMatching2026"
title: "ActSafeGuard: Differentiable and Training-Aligned Constraint Enforcement for Flow-Matching Policies"
authors: ["Jianming Ma", "Rongjun Jin", "Xiaxi Si", "Yang Zhang", "Yiheng Li", "Yue Gao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.11697"
doi: "10.48550/arXiv.2609.11697"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-09-12
---

# ActSafeGuard: Differentiable and Training-Aligned Constraint Enforcement for Flow-Matching Policies

> Jianming Ma, Rongjun Jin, Xiaxi Si, Yang Zhang, Yiheng Li, Yue Gao · 2026
> [arXiv](https://arxiv.org/abs/2609.11697) · [PDF](https://arxiv.org/pdf/2609.11697)

## Abstract

Vision-Language-Action (VLA) and World-Action Models (WAMs) have demonstrated strong capabilities in general-purpose robotic manipulation, yet their generated actions may violate hard physical constraints and therefore be unsafe or infeasible for deployment. Existing safety approaches either optimize statistical safety objectives without deterministic per-step guarantees or correct unsafe actions only during inference, creating a mismatch between policy training and execution. We introduce ActSafeGuard, a differentiable and training-aligned safeguard layer for flow-matching based policies. ActSafeGuard integrates hard action feasibility into policy learning, not merely treating safety as an inference-time external component. Through an analytical ray-scaling operator design, ActSafeGuard enables boundary-aware gradients to guide the model to naturally learn constrained manifolds. Extensive experiments on multiple standard foundation backbones ($\pi_{0.5}$ and Fast-WAM) across various tasks demonstrate that ActSafeGuard consistently achieves a $100\%$ step safety rate while fully preserving or even boosting task success rates, providing a scalable and minimally invasive solution for safe embodied AI deployment.

## TL;DR

Vision-Language-Action (VLA) and World-Action Models (WAMs) have demonstrated strong capabilities in general-purpose robotic manipulation, yet their generated actions may violate hard physical constraints and therefore be unsafe or infeasible for deployment. Existing safety approaches either optimize statistical safety objectives without deterministic per-step guarantees or correct unsafe actions only during inference, creating a mismatch between policy training and execution.

## Related
<!-- [[other-paper-citekey]] -->
