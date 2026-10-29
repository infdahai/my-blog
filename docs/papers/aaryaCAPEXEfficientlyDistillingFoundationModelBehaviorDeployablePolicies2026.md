---
citekey: "aaryaCAPEXEfficientlyDistillingFoundationModelBehaviorDeployablePolicies2026"
title: "CAPEX: Efficiently Distilling Foundation Model Behavior into Deployable Robot Policies through Experience-Adaptive Reasoning"
authors: ["Shivam Aarya", "Zhang Xi-Jia", "Chengyue Huang", "Junhyun Kim", "Huishu Xue", "Hrishit Leen", "Roman Yakunin", "Animesh Garg", "Zsolt Kira"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.33007"
doi: "10.48550/arXiv.2609.33007"
tags: [paper, embodied-ai, "cs.AI", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# CAPEX: Efficiently Distilling Foundation Model Behavior into Deployable Robot Policies through Experience-Adaptive Reasoning

> Shivam Aarya, Zhang Xi-Jia, Chengyue Huang, Junhyun Kim, Huishu Xue, Hrishit Leen, Roman Yakunin, Animesh Garg, Zsolt Kira · 2026
> [arXiv](https://arxiv.org/abs/2609.33007) · [PDF](https://arxiv.org/pdf/2609.33007)

## Abstract

Robot learning has largely relied on human-teleoperated demonstrations to acquire effective learnable behaviors. However, human-operated data collection processes can be unintuitive, difficult to scale, and inherently asynchronous. We explore an alternative: distilling physical behavior from general-purpose multimodal foundation models into deployable robot policies by using the foundation model itself as an autonomous demonstrator. While sufficiently capable models can generate successful zero-shot manipulation trajectories, repeatedly invoking them during physical execution is slow and expensive, limiting their utility as scalable data generators. As a solution, we introduce CAPEX, an experience-conditioned demonstration collection framework that uses execution experience from previous attempts to adapt how frequently the foundation model must observe, reason, and replan. We evaluate across RoboCasa tasks and on physical Franka and bimanual YAM-arm platforms, measuring task success, model calls, token usage, collection time, and cost. We further train Diffusion Policy and ACT on matched sets of human-teleoperated and foundation-model-generated demonstrations to evaluate the downstream learning value of autonomously collected data. We find that CAPEX increases the number of successful demonstrations by 4.3x while reducing the cost per successful demonstration by 80%. Policies trained on CAPEX-generated data approach the performance of those trained on matched human demonstrations; with longer training, this gap largely closes for policies trained from scratch. These results suggest that foundation models can serve as scalable sources of reusable robot experience. Project page: https://capex-paper.github.io/

## TL;DR

Robot learning has largely relied on human-teleoperated demonstrations to acquire effective learnable behaviors. However, human-operated data collection processes can be unintuitive, difficult to scale, and inherently asynchronous.

## Related
<!-- [[other-paper-citekey]] -->
