---
citekey: "parkIsOnlineInteractionNecessaryRecoveryMinimalistApproachRobust2026"
title: "Is Online Interaction Necessary for Recovery? A Minimalist Approach to Robust Planning via Perturbation"
authors: ["Bumgeun Park", "Donghwan Lee"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.33049"
doi: "10.48550/arXiv.2609.33049"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# Is Online Interaction Necessary for Recovery? A Minimalist Approach to Robust Planning via Perturbation

> Bumgeun Park, Donghwan Lee · 2026
> [arXiv](https://arxiv.org/abs/2609.33049) · [PDF](https://arxiv.org/pdf/2609.33049)

## Abstract

Behavior cloning (BC) is vulnerable to covariate shift during closed-loop execution, where small prediction or execution errors can drive the robot toward states poorly covered by the demonstration data. We focus on action-sequence planning, where a policy predicts a finite-horizon sequence of actions as a reference trajectory for robot execution. Existing approaches to covariate shift often rely on collecting additional corrective demonstrations, requiring further environment interaction and access to an expert or reference policy. We propose Perturbation-Augmented Recovery Supervision (PARS), a simple training approach for improving recovery using only existing demonstrations. PARS perturbs the robot's proprioceptive state and anchors only the later portion of the predicted trajectory to the original demonstration, leaving the earlier portion free to generate corrective motion and recover toward the demonstrated behavior within the planning horizon. Unlike conventional input-noise augmentation, which preserves the original supervision target over the entire prediction horizon, PARS explicitly provides trajectory-level supervision for recovery from perturbed states. PARS requires neither additional environment interaction nor expert queries and can be instantiated across different action-sequence policy classes with only minor modifications to their BC objectives. Experiments on 51 RLBench manipulation tasks with flow-based, transformer-based, and diffusion-based policies demonstrate that PARS improves robustness to covariate shift during closed-loop execution.

## TL;DR

Behavior cloning (BC) is vulnerable to covariate shift during closed-loop execution, where small prediction or execution errors can drive the robot toward states poorly covered by the demonstration data. We focus on action-sequence planning, where a policy predicts a finite-horizon sequence of actions as a reference trajectory for robot execution.

## Related
<!-- [[other-paper-citekey]] -->
