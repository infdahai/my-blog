---
citekey: "joualyScalingVisionLanguageRewardLearningManipulationParallelSimulation2026"
title: "Scaling Vision-Language Reward Learning for Robot Manipulation in Parallel Simulation"
authors: ["Lobna Joualy", "Eric Demeester", "Nikolaos Tsiogkas"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.21767"
doi: "10.48550/arXiv.2609.21767"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-22
---

# Scaling Vision-Language Reward Learning for Robot Manipulation in Parallel Simulation

> Lobna Joualy, Eric Demeester, Nikolaos Tsiogkas · 2026
> [arXiv](https://arxiv.org/abs/2609.21767) · [PDF](https://arxiv.org/pdf/2609.21767)

## Abstract

Vision-language models (VLMs) can replace human annotators in preference-based reward learning, but sequential API requests and single-environment data collection make training slow and costly. We present RAPID (Reward learning with Adaptive Parallel Image Diversity), a system that couples GPU-parallel rollout with data-aware policy updates, single-request preference labeling, automatic reward stabilization, and representative image sampling. We evaluate these components on five Franka Panda manipulation tasks in IsaacLab. Parallel rollout and adaptive updates provide the first substantial reduction in training time: under matched two-stage prompting, mean runtime falls from 9.18 to 3.13 hours. With all RAPID components enabled, training completes in 1.15 hours using 896 rather than 19,840 API calls per run, and aggregate final success rises from 86.3\% to 98.7\%. This represents an 8.0$\times$ end-to-end speedup and a 95.5\% reduction in API usage. An offline evaluation with Gemma~3 12B and GPT-4.1 mini demonstrates that single-request prompting reduces labeling latency and cost across both models. Code is available at: https://github.com/rapid-vlm/rapid-vlm-rl.

## TL;DR

Vision-language models (VLMs) can replace human annotators in preference-based reward learning, but sequential API requests and single-environment data collection make training slow and costly. We present RAPID (Reward learning with Adaptive Parallel Image Diversity), a system that couples GPU-parallel rollout with data-aware policy updates, single-request preference labeling, automatic reward stabilization, and representative image sampling.

## Related
<!-- [[other-paper-citekey]] -->
