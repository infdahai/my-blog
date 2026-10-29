---
citekey: "yangScaleNavScalableInternetVideoPretrainingLanguageConditionedLocal2026"
title: "ScaleNav: Scalable Internet Video Pretraining for Language-Conditioned Local Navigation"
authors: ["Yihui Yang", "Yuanhong Yu", "Jiawei Wang", "Zhongrui Yu", "Jia Shi", "Kun Zhan", "Ruizhen Hu", "Xiaowei Zhou", "Yu Liu", "Sida Peng"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.25690"
doi: "10.48550/arXiv.2610.25690"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-22
---

# ScaleNav: Scalable Internet Video Pretraining for Language-Conditioned Local Navigation

> Yihui Yang, Yuanhong Yu, Jiawei Wang, Zhongrui Yu, Jia Shi, Kun Zhan, Ruizhen Hu, Xiaowei Zhou, Yu Liu, Sida Peng · 2026
> [arXiv](https://arxiv.org/abs/2610.25690) · [PDF](https://arxiv.org/pdf/2610.25690)

## Abstract

We study language-conditioned local navigation, where a robot must navigate to a text-specified target visible in its initial observation and stop at the described location. End-to-end navigation policies require diverse training data to generalize across scenes, yet real-robot data is costly to collect and simulated data leaves a sim-to-real gap. Internet egocentric videos offer a scalable source of real-world navigation experience. Our key insight is to learn goal-directed visual dynamics from Internet egocentric videos, and use these dynamics to support robot action generation. To this end, we propose ScaleNav, a unified world-action framework with three-stage training. We first perform instruction-conditioned video pretraining on these videos to learn how observations evolve as the camera approaches instructed targets across diverse real-world scenes. Action alignment then uses action-labeled simulated data to train the model to predict executable action chunks. Joint fine-tuning subsequently optimizes all trainable components together for navigation. ScaleNav achieves success rates of 86.5% on a single-view adaptation of Short-Horizon OVON and 94.9% on our HabitatGS-LN benchmark, outperforming the evaluated baselines on both benchmarks. We further deploy and evaluate ScaleNav on a real quadruped robot, with results supporting the model's ability to generalize to real-world navigation. Code and videos are available at https://zju3dv.github.io/ScaleNav/

## TL;DR

We study language-conditioned local navigation, where a robot must navigate to a text-specified target visible in its initial observation and stop at the described location. End-to-end navigation policies require diverse training data to generalize across scenes, yet real-robot data is costly to collect and simulated data leaves a sim-to-real gap.

## Related
<!-- [[other-paper-citekey]] -->
