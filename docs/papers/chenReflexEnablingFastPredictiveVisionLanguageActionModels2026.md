---
citekey: "chenReflexEnablingFastPredictiveVisionLanguageActionModels2026"
title: "Reflex: Enabling Fast and Predictive Vision-Language-Action Models for Reaction-Critical Manipulation"
authors: ["Yuxuan Chen", "Wanruo Zhang", "Xiao Li"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.14379"
doi: "10.48550/arXiv.2608.14379"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# Reflex: Enabling Fast and Predictive Vision-Language-Action Models for Reaction-Critical Manipulation

> Yuxuan Chen, Wanruo Zhang, Xiao Li · 2026
> [arXiv](https://arxiv.org/abs/2608.14379) · [PDF](https://arxiv.org/pdf/2608.14379)

## Abstract

Vision-Language-Action (VLA) models have recently achieved promising performance in robotic manipulation. However, existing benchmarks mainly evaluate generalization on static manipulation tasks and largely overlook dynamic interaction scenarios. To address this gap, we present ReflexBench, a benchmark for reaction-critical manipulation. ReflexBench contains six dynamic tasks and introduces an evaluation framework that decouples simulator stepping from robot control while supporting configurable latency under synchronous and asynchronous inference. Building upon ReflexBench, we propose ReflexVLA, an efficient VLA model designed for reaction-critical manipulation without large-scale robot-data pretraining. ReflexVLA enhances temporal reasoning through latent future prediction and multi-frame temporal fusion within the vision backbone, while reducing deployment latency through batched visual encoding and CUDA Graph replay. Experiments show that ReflexVLA consistently improves dynamic manipulation performance while maintaining competitive accuracy on standard static manipulation benchmarks, and real-world experiments further demonstrate its effectiveness under practical deployment conditions. Project website: https://reflexvla.github.io

## TL;DR

Vision-Language-Action (VLA) models have recently achieved promising performance in robotic manipulation. However, existing benchmarks mainly evaluate generalization on static manipulation tasks and largely overlook dynamic interaction scenarios.

## Related
<!-- [[other-paper-citekey]] -->
