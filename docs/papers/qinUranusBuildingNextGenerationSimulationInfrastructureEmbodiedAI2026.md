---
citekey: "qinUranusBuildingNextGenerationSimulationInfrastructureEmbodiedAI2026"
title: "Uranus: Building the Next-Generation Simulation Infrastructure for Embodied AI"
authors: ["Wenkang Qin", "Yukun Zhou", "Noah Shen", "Jisong Cai", "Dongxiao Mao", "Baicheng Li", "Yue Zhang", "Wei Sui"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.24815"
doi: "10.48550/arXiv.2609.24815"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-09-23
---

# Uranus: Building the Next-Generation Simulation Infrastructure for Embodied AI

> Wenkang Qin, Yukun Zhou, Noah Shen, Jisong Cai, Dongxiao Mao, Baicheng Li, Yue Zhang, Wei Sui · 2026
> [arXiv](https://arxiv.org/abs/2609.24815) · [PDF](https://arxiv.org/pdf/2609.24815)

## Abstract

Scalable simulation is essential for robot data generation, policy training, evaluation, and safe iteration, yet real-world interaction is costly and conventional simulators require labor-intensive construction. We present Uranus, a data-driven robot simulator built around a joint-trajectory-conditioned autoregressive diffusion model. Uranus offers three key capabilities: (1) streaming, open-ended rollout, which receives future joint-position trajectories online and autoregressively generates one latent frame per step, corresponding to four RGB frames, without a fixed horizon; (2) low-latency generation, achieving 24 FPS after inference optimization; and (3) scalable, extensible robot control, providing a unified interface for synchronized multi-view generation across diverse robot embodiments and camera configurations. We conduct comprehensive quantitative and qualitative evaluations on both in-distribution and out-of-distribution data, providing an objective assessment of Uranus and clearly identifying its current limitations. We release the code and model weights to empower the community with practical tools and insights.

## TL;DR

Scalable simulation is essential for robot data generation, policy training, evaluation, and safe iteration, yet real-world interaction is costly and conventional simulators require labor-intensive construction. We present Uranus, a data-driven robot simulator built around a joint-trajectory-conditioned autoregressive diffusion model.

## Related
<!-- [[other-paper-citekey]] -->
