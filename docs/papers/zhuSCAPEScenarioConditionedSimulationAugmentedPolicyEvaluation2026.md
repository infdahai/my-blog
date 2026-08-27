---
citekey: "zhuSCAPEScenarioConditionedSimulationAugmentedPolicyEvaluation2026"
title: "SCAPE: Scenario-Conditioned Simulation-Augmented Policy Evaluation"
authors: ["Dijie Zhu", "Seunghun Oh", "Ruopeng Huang", "Zhiyu Huang", "Jiaqi Ma", "Chen Tang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.19425"
doi: "10.48550/arXiv.2608.19425"
tags: [paper, embodied-ai, "cs.AI", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# SCAPE: Scenario-Conditioned Simulation-Augmented Policy Evaluation

> Dijie Zhu, Seunghun Oh, Ruopeng Huang, Zhiyu Huang, Jiaqi Ma, Chen Tang · 2026
> [arXiv](https://arxiv.org/abs/2608.19425) · [PDF](https://arxiv.org/pdf/2608.19425)

## Abstract

Reliable performance evaluation is a central bottleneck for deploying robot-learning policies in real-world conditions. Real-world testing is faithful but costly and difficult to scale, whereas simulation-based testing scales easily but is inevitably biased by the sim-to-real gap. Existing simulation-augmented methods combine limited real-world rollouts with abundant simulation proxies, but focus on performance averaged over initial conditions and deployment settings. Such population-level averages obscure scenario-specific variation and provide limited guidance about when and where a policy can be safely deployed. We propose SCAPE, a scenario-conditioned simulation-augmented policy evaluation framework that predicts scenario-conditioned real-world policy performance using limited paired sim-and-real samples and large-scale simulation rollouts. SCAPE corrects sim-to-real bias in simulation labels before training the prediction model and calibrates prediction uncertainty through conformal prediction. We validate SCAPE on autonomous driving and quadruped velocity tracking. In sim-to-sim studies, SCAPE reduces scenario-level prediction error by 4.9%/34.7% (driving) and 14.5%/27.7% (quadruped) relative to scene-conditioned neural and aggregate statistical baselines on average. We further evaluate a velocity-tracking policy deployed on a physical Unitree Go2. SCAPE also improves testing sample efficiency, produces narrower calibrated prediction intervals, generalizes better to out-of-distribution scenarios, and enables fine-grained deployment strategies.

## TL;DR

Reliable performance evaluation is a central bottleneck for deploying robot-learning policies in real-world conditions. Real-world testing is faithful but costly and difficult to scale, whereas simulation-based testing scales easily but is inevitably biased by the sim-to-real gap.

## Related
<!-- [[other-paper-citekey]] -->
