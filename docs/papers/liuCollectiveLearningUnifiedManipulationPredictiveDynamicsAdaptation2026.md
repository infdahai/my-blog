---
citekey: "liuCollectiveLearningUnifiedManipulationPredictiveDynamicsAdaptation2026"
title: "Collective Learning for Unified Robotic Manipulation via Predictive Dynamics Adaptation"
authors: ["Shaocheng Liu", "Yuan Meng", "Zhenshan Bing", "Alois Knoll"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.19141"
doi: "10.48550/arXiv.2610.19141"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-16
---

# Collective Learning for Unified Robotic Manipulation via Predictive Dynamics Adaptation

> Shaocheng Liu, Yuan Meng, Zhenshan Bing, Alois Knoll · 2026
> [arXiv](https://arxiv.org/abs/2610.19141) · [PDF](https://arxiv.org/pdf/2610.19141)

## Abstract

Learning a collective policy for state-based Cartesian manipulation across diverse robotic embodiments presents a fundamental challenge due to embodiment-dependent transition dynamics. Collective learning aggregates multi-robot experience to discover shared task structure, yet naive aggregation can average incompatible action modes when different embodiments realize the same Cartesian command through different transition behavior. This leads to strategy ambiguity and performance collapse on dynamically outlying embodiments. To address this, we propose PACE, a two-stage collective learning framework that separates shared task-space intent from embodiment-dependent transition dynamics. The first stage employs a representation layer pre-trained on offline trajectories to extract task-level context from collective data. The second stage introduces a decision layer equipped with a predictive dynamics adapter. By forcing the latent state to predict future transitions, this adapter acts as a latent regularizer that grounds the policy in the transition behavior of the executing robot while preserving real-time inference without online planning. Evaluations across simulated embodiments demonstrate that our method prevents performance collapse on distinct robots. It achieves over 93\% overall success and 89\% on dynamically out-of-distribution zero-shot simulated robots, outperforming the Transformer behavior cloning (82\%) and diffusion policy baselines (66\%). Physical KUKA deployment further validates the feasibility of the full state-based pipeline under zero-shot sim-to-real transfer.

## TL;DR

Learning a collective policy for state-based Cartesian manipulation across diverse robotic embodiments presents a fundamental challenge due to embodiment-dependent transition dynamics. Collective learning aggregates multi-robot experience to discover shared task structure, yet naive aggregation can average incompatible action modes when different embodiments realize the same Cartesian command through different transition behavior.

## Related
<!-- [[other-paper-citekey]] -->
