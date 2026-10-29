---
citekey: "liScoutingDynamicsGapTestTimePolicyAdaptationAction2026"
title: "Scouting the Dynamics Gap: Test-Time Policy Adaptation via Action-Outcome Feedback"
authors: ["Yishu Li", "Liyuan Geng", "Xinyi Mao", "Amber Li", "David Held"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.36107"
doi: "10.48550/arXiv.2609.36107"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# Scouting the Dynamics Gap: Test-Time Policy Adaptation via Action-Outcome Feedback

> Yishu Li, Liyuan Geng, Xinyi Mao, Amber Li, David Held · 2026
> [arXiv](https://arxiv.org/abs/2609.36107) · [PDF](https://arxiv.org/pdf/2609.36107)

## Abstract

While pretrained robotic policies exhibit impressive capabilities in controlled environments, unobserved physical properties and dynamics require these policies to rapidly adapt during deployment. Existing test-time adaptation methods typically rely on sparse scalar rewards, failing to exploit the rich geometric and dynamic feedback from the environment during physical interaction. To address this challenge, we propose SCOUT, a dynamics-aware meta-learning framework that enables manipulation policies to rapidly adapt by continuously revising their internal beliefs about environment dynamics. Our approach couples an action-prediction policy with a forward dynamics model via a shared belief latent space. During meta-training, an inner loop updates this shared belief latent by minimizing the dynamics prediction error against the observed action outcome, while the outer loop optimizes the network for action selection. At deployment, this structure allows the agent to infer and adapt to unknown physical dynamics on the fly. By updating its latent belief based on action-outcome mismatches, the policy automatically adapts without risking catastrophic forgetting. We demonstrate that SCOUT significantly accelerates online adaptation across simulated manipulation benchmarks and achieves robust sim-to-real transfer in the real world. Project webiste can be found here: https://liy1shu.github.io/SCOUT/

## TL;DR

While pretrained robotic policies exhibit impressive capabilities in controlled environments, unobserved physical properties and dynamics require these policies to rapidly adapt during deployment. Existing test-time adaptation methods typically rely on sparse scalar rewards, failing to exploit the rich geometric and dynamic feedback from the environment during physical interaction.

## Related
<!-- [[other-paper-citekey]] -->
