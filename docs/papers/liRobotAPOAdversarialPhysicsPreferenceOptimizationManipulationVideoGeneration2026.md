---
citekey: "liRobotAPOAdversarialPhysicsPreferenceOptimizationManipulationVideoGeneration2026"
title: "RobotAPO: Adversarial Physics Preference Optimization for Robotic Manipulation Video Generation"
authors: ["Kerui Li", "Zhe Jing", "Chenyi Huang", "Xiaofeng Wang", "Zheng Zhu", "Haoming Cui", "Huaibo Huang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.09454"
doi: "10.48550/arXiv.2610.09454"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-09
---

# RobotAPO: Adversarial Physics Preference Optimization for Robotic Manipulation Video Generation

> Kerui Li, Zhe Jing, Chenyi Huang, Xiaofeng Wang, Zheng Zhu, Haoming Cui, Huaibo Huang · 2026
> [arXiv](https://arxiv.org/abs/2610.09454) · [PDF](https://arxiv.org/pdf/2610.09454)

## Abstract

Robotic manipulation videos are increasingly used as visual plans for embodied agents, but optimizing purely for visual plausibility often fails to capture the fragile physical manifold of real-world interactions. Even minor physics-violating errors at the interaction boundary, such as interpenetration or premature object motion, can completely invalidate the inferred timing and pose needed for downstream execution. Because standard supervised fine-tuning lacks the direct pressure to penalize these localized failures, we introduce AgiBot-PhysPref. This rigorously curated 10,000-sample preference dataset isolates condition-matched physics violations, turning the generator's own failure distribution into a foundational signal for physical consistency. Building upon this, we propose RobotAPO, an adversarial physics preference optimization framework operating in the continuous flow-matching denoising space. To prevent the policy from merely memorizing static curated failures, RobotAPO employs a lightweight adversarial counterfactual proposer that learns a condition-dependent, physical-failure-biased direction in denoising space. This encourages the model to explore and better respect the physical interaction boundary, all while maintaining a pure prompt-and-reference inference interface without requiring external structural conditioning. Comprehensive evaluations demonstrate that explicitly correcting these localized physics violations improves downstream robot execution from generated videos. On held-out AgiBot conditions, RobotAPO outperforms the strongest controlled internal baseline in physical consistency by 6.8% hard score and 10.0% soft score. Crucially, in real-robot replay, it translates these physical-consistency gains into a 37.4% relative improvement in task success over the strongest controlled internal baseline.

## TL;DR

Robotic manipulation videos are increasingly used as visual plans for embodied agents, but optimizing purely for visual plausibility often fails to capture the fragile physical manifold of real-world interactions. Even minor physics-violating errors at the interaction boundary, such as interpenetration or premature object motion, can completely invalidate the inferred timing and pose needed for downstream execution.

## Related
<!-- [[other-paper-citekey]] -->
