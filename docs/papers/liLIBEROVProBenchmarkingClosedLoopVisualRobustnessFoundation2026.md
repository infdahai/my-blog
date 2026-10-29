---
citekey: "liLIBEROVProBenchmarkingClosedLoopVisualRobustnessFoundation2026"
title: "LIBERO-VPro: Benchmarking Closed-Loop Visual Robustness of Robotic Foundation Models"
authors: ["Huiqiong Li", "Zhiting Mei", "Anirudha Majumdar", "Jingjing Chen", "Yu-Gang Jiang", "Bin Zhu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.24350"
doi: "10.48550/arXiv.2609.24350"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-23
---

# LIBERO-VPro: Benchmarking Closed-Loop Visual Robustness of Robotic Foundation Models

> Huiqiong Li, Zhiting Mei, Anirudha Majumdar, Jingjing Chen, Yu-Gang Jiang, Bin Zhu · 2026
> [arXiv](https://arxiv.org/abs/2609.24350) · [PDF](https://arxiv.org/pdf/2609.24350)

## Abstract

Robotic foundation models achieve impressive performance on standard manipulation benchmarks, yet these evaluations typically assume clean, timely, and consistent visual observations throughout execution. We introduce LIBERO-VPro, a benchmark for systematically evaluating the closed-loop visual robustness of robotic foundation models by perturbing the visual evidence available during execution. LIBERO-VPro covers four complementary dimensions, including Visual Evidence Degradation, Camera Staleness, Visual Source Consistency, and Task-Relevant Scene Variation, spanning 12 challenge categories, 96 experimental settings, and 3,296 task-condition cases. We evaluate three vision-language-action models and three world-action models over approximately 196,000 simulated episodes, complemented by 200 real-world rollouts on a Franka Research 3. Our results reveal that strong nominal performance can mask substantial weaknesses in visual grounding and adaptation. Models often remain successful despite severe object-level occlusion, yet degrade sharply when local interaction cues are disrupted or familiar spatial priors are violated. They are also highly sensitive to stale or missing observations and struggle when changed task preconditions require behavioral adaptation. Finally, VLAs and WAMs exhibit distinct robustness profiles, showing that visual robustness is multi-dimensional and architecture-dependent. LIBERO-VPro provides a systematic diagnostic framework for developing robotic foundation models that can more reliably ground and adapt their actions under challenging visual conditions.

## TL;DR

Robotic foundation models achieve impressive performance on standard manipulation benchmarks, yet these evaluations typically assume clean, timely, and consistent visual observations throughout execution. We introduce LIBERO-VPro, a benchmark for systematically evaluating the closed-loop visual robustness of robotic foundation models by perturbing the visual evidence available during execution.

## Related
<!-- [[other-paper-citekey]] -->
