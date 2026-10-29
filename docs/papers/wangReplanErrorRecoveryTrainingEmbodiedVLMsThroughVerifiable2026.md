---
citekey: "wangReplanErrorRecoveryTrainingEmbodiedVLMsThroughVerifiable2026"
title: "Replan for Error Recovery: Training Embodied VLMs through Verifiable Interaction with Action-Grouped Turn-GSPO"
authors: ["Zhuoran Wang", "Keqing Fan", "Yang Li", "Jinbo Su", "Ke Wang", "Sijia Luo", "Yuanzheng Tan", "Junken Peng", "Jing Zhang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.27003"
doi: "10.48550/arXiv.2610.27003"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-22
---

# Replan for Error Recovery: Training Embodied VLMs through Verifiable Interaction with Action-Grouped Turn-GSPO

> Zhuoran Wang, Keqing Fan, Yang Li, Jinbo Su, Ke Wang, Sijia Luo, Yuanzheng Tan, Junken Peng, Jing Zhang · 2026
> [arXiv](https://arxiv.org/abs/2610.27003) · [PDF](https://arxiv.org/pdf/2610.27003)

## Abstract

Embodied VLMs can execute increasingly complex manipulation tasks, yet execution errors can leave the environment in states that require replanning for recovery. Existing recovery methods either rely on inference-time mechanisms with fixed policies or learn from failure examples and reference corrections rather than verified action outcomes. To enable recovery learning through verifiable interaction, we introduce the Embodied Replanning for Recovery Environment (ERR-Env), which provides feedback on task progress and execution errors. We further construct ERR-Bench, a benchmark with held-out tasks spanning nominal, intermediate, and error states for evaluating recovery capability and execution reliability. We then propose Action-Grouped Turn-GSPO (AGT-GSPO), an online reinforcement learning method combining turn-level rewards for task progress and error states with action-grouped advantage estimation, and use it to train ERR-VLM, a compact 2B embodied VLM. Evaluation on ERR-Bench reveals a mismatch between task progress and execution reliability across diverse VLMs. AGT-GSPO improves ERR-VLM by 10.25 percentage points in Strict Success Rate for error-free completion and 22.95 percentage points in Recovery Rate, while ablations and zero-shot transfer further validate the effectiveness of our method.

## TL;DR

Embodied VLMs can execute increasingly complex manipulation tasks, yet execution errors can leave the environment in states that require replanning for recovery. Existing recovery methods either rely on inference-time mechanisms with fixed policies or learn from failure examples and reference corrections rather than verified action outcomes.

## Related
<!-- [[other-paper-citekey]] -->
