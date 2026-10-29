---
citekey: "liuRecovaAgentGuidedFailureRecoveryAutonomousManipulation2026"
title: "Recova: Agent-Guided Failure Recovery for Autonomous Robotic Manipulation"
authors: ["Isabella Liu", "An-Chieh Cheng", "Johan Bjorck", "Zhiding Yu", "Hongxu Yin", "Jan Kautz", "Linxi Fan", "Yuke Zhu", "Sifei Liu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.01178"
doi: "10.48550/arXiv.2610.01178"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# Recova: Agent-Guided Failure Recovery for Autonomous Robotic Manipulation

> Isabella Liu, An-Chieh Cheng, Johan Bjorck, Zhiding Yu, Hongxu Yin, Jan Kautz, Linxi Fan, Yuke Zhu, Sifei Liu · 2026
> [arXiv](https://arxiv.org/abs/2610.01178) · [PDF](https://arxiv.org/pdf/2610.01178)

## Abstract

Manipulation failures can leave scenes in states from which a task policy cannot recover. Learning corrective behaviors requires scalable failure exploration and physical grounding. We present Recova, an agent-guided framework that jointly develops task execution and recovery in a reconstructed digital twin, then verifies and refines both through real-world experience. In the twin, the agent diagnoses failures, tests corrective programs, and collects successful task and recovery rollouts for separate policies. During deployment, it monitors progress, invokes a learned or programmatic recovery, verifies scene restoration, and resumes execution. When no suitable recovery is available, a human demonstration resolves the failure and enters the learning loop, allowing the system to expand its recovery capabilities. Physical rollouts and human demonstrations are routed to the corresponding policy for DAgger training. Across six LIBERO-Pro settings and four MolmoSpaces categories, Recova achieves 78.8% and 64.9% mean success, compared with 71.7% and 38.0% for the strongest baselines. With parallel collection across four real-robot workstations, DAgger fine-tuning raises mean success from 23.8% to 77.5%, and recovery skills further raise it to 87.5%. Over four collection rounds on one task, observed human intervention falls from 87.5% to 0%. Together, these results show how agent-guided recovery turns failures into reusable capabilities, improving robustness while progressively reducing human intervention. Project page: https://www.liuisabella.com/Recova

## TL;DR

Manipulation failures can leave scenes in states from which a task policy cannot recover. Learning corrective behaviors requires scalable failure exploration and physical grounding.

## Related
<!-- [[other-paper-citekey]] -->
