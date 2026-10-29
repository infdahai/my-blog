---
citekey: "wangTaskPrototypeGuidedFlowMatchingFewShotGeneralization2026"
title: "Task-Prototype Guided Flow Matching for Few-Shot Generalization in Vision-Language Robot Manipulation"
authors: ["Yizhao Wang", "Guantao Zhang", "Jingbo Wang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.27780"
doi: "10.48550/arXiv.2609.27780"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-25
---

# Task-Prototype Guided Flow Matching for Few-Shot Generalization in Vision-Language Robot Manipulation

> Yizhao Wang, Guantao Zhang, Jingbo Wang · 2026
> [arXiv](https://arxiv.org/abs/2609.27780) · [PDF](https://arxiv.org/pdf/2609.27780)

## Abstract

Vision-language robot manipulation policies can follow semantic instructions, but adapting them to a new procedure from only a few demonstrations remains difficult because language underspecifies contact timing, motion phases, corrective behavior, and execution style. This paper presents Task-Prototype Guided Flow Matching (TP-Flow), a few-shot manipulation framework that converts support demonstrations into structured task-prototype tokens and uses them to guide both the initial flow prior and the velocity field. TP-Flow employs symmetric cross-attention with learnable queries to extract phase-level prototypes, parameterizes a task-adaptive initial distribution, and injects prototype information through gated adaptive normalization. It is trained with an episodic support-query objective and prototype contrastive regularization, so few-shot adaptation is simulated during training while nuisance information is suppressed. On the LEROBOT-ARM-SO101 platform, TP-Flow achieves 66.8\%, 79.6\%, and 82.1\% success rates under 1-, 4-, and 6-shot settings, with a 75.5\% few-shot AUC. At 1-shot, it improves over CFM, Pooled-Demo CFM, and In-Context Flow by 29.8, 14.5, and 9.9 percentage points. It also improves held-out target-group generalization across novel-object transfer, goal recombination, long-horizon composition, and contact/correction tasks. TP-Flow maintains real-time execution with six online prototype tokens, 54.3 ms latency, 3.9 GB peak memory, and a 10 Hz control rate, while reducing the noisy-support success drop to 6.2\%. Theoretical diagnostics show that prototype distance aligns with action-distribution distance, the adaptive prior reduces transport cost, and gated modulation keeps measured trajectory deviations below the derived ODE bound. The code repository is omitted for anonymous review.

## TL;DR

Vision-language robot manipulation policies can follow semantic instructions, but adapting them to a new procedure from only a few demonstrations remains difficult because language underspecifies contact timing, motion phases, corrective behavior, and execution style. This paper presents Task-Prototype Guided Flow Matching (TP-Flow), a few-shot manipulation framework that converts support demonstrations into structured task-prototype tokens and uses them to guide both the initial flow prior and the velocity field.

## Related
<!-- [[other-paper-citekey]] -->
