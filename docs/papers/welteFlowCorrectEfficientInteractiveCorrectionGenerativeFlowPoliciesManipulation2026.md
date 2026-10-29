---
citekey: "welteFlowCorrectEfficientInteractiveCorrectionGenerativeFlowPoliciesManipulation2026"
title: "FlowCorrect: Efficient Interactive Correction of Generative Flow Policies for Robotic Manipulation"
authors: ["Edgar Welte", "Yitian Shi", "Rosa Wolf", "Maximillian Gilles", "Rania Rayyes"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2602.22056"
doi: "10.48550/arXiv.2602.22056"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-09-01
---

# FlowCorrect: Efficient Interactive Correction of Generative Flow Policies for Robotic Manipulation

> Edgar Welte, Yitian Shi, Rosa Wolf, Maximillian Gilles, Rania Rayyes · 2026
> [arXiv](https://arxiv.org/abs/2602.22056) · [PDF](https://arxiv.org/pdf/2602.22056)

## Abstract

Generative manipulation policies can fail catastrophically under deployment-time distribution shift, yet many failures are near-misses: the robot reaches almost-correct poses and would succeed with a small corrective motion. We propose FlowCorrect, a modular interactive imitation learning approach that enables deployment-time adaptation of flow-matching manipulation policies from sparse, relative human corrections without retraining. During execution, a human provides brief corrective pose nudges via a lightweight VR interface. FlowCorrect uses these sparse corrections to locally adapt the policy, improving actions without retraining the backbone while preserving the model performance on previously learned scenarios. We evaluate on a real-world robot across four tabletop tasks: pick-and-place, pouring, cup uprighting, and insertion. With a low correction budget, FlowCorrect achieves an 80% success rate on previously failed cases while preserving performance on previously solved scenarios. The results clearly demonstrate that FlowCorrect learns from very few demonstrations and enables fast, sample-efficient, incremental, human-in-the-loop corrections of generative visuomotor policies at deployment time in real-world robotics.

## TL;DR

Generative manipulation policies can fail catastrophically under deployment-time distribution shift, yet many failures are near-misses: the robot reaches almost-correct poses and would succeed with a small corrective motion. We propose FlowCorrect, a modular interactive imitation learning approach that enables deployment-time adaptation of flow-matching manipulation policies from sparse, relative human corrections without retraining.

## Related
<!-- [[other-paper-citekey]] -->
