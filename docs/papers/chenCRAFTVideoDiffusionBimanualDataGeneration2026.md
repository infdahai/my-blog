---
citekey: "chenCRAFTVideoDiffusionBimanualDataGeneration2026"
title: "CRAFT: Video Diffusion for Bimanual Robot Data Generation"
authors: ["Jason Chen", "I-Chun Arthur Liu", "Gaurav Sukhatme", "Daniel Seita"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2604.03552"
doi: "10.48550/arXiv.2604.03552"
tags: [paper, embodied-ai, "cs.AI", "cs.CV", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# CRAFT: Video Diffusion for Bimanual Robot Data Generation

> Jason Chen, I-Chun Arthur Liu, Gaurav Sukhatme, Daniel Seita · 2026
> [arXiv](https://arxiv.org/abs/2604.03552) · [PDF](https://arxiv.org/pdf/2604.03552)

## Abstract

Bimanual robot learning from demonstrations is fundamentally limited by the cost and narrow visual diversity of real-world data, which constrains policy robustness across viewpoints, object configurations, and embodiments. We present Canny-guided Robot Data Generation using Video Diffusion Transformers (CRAFT), a video diffusion-based framework for scalable bimanual demonstration generation that synthesizes temporally coherent manipulation videos while producing action labels. By conditioning video diffusion on edge-based structural cues extracted from simulator-generated trajectories, CRAFT produces physically plausible trajectory variations and supports a unified augmentation pipeline spanning object pose changes, camera viewpoints, lighting and background variations, cross-embodiment transfer, and multi-view synthesis. We leverage a pre-trained video diffusion model to convert simulated videos, along with action labels from the simulation trajectories, into action-consistent demonstrations. Starting from only a few real-world demonstrations, CRAFT generates a large, visually diverse set of photorealistic training data, bypassing the need to replay demonstrations on the real robot (Sim2Real). Across simulated and real-world bimanual tasks, CRAFT improves success rates over existing augmentation strategies and straightforward data scaling, demonstrating that diffusion-based video generation can substantially expand demonstration diversity and improve generalization for dual-arm manipulation tasks. Our project website is available at: https://craftaug.github.io/

## TL;DR

Bimanual robot learning from demonstrations is fundamentally limited by the cost and narrow visual diversity of real-world data, which constrains policy robustness across viewpoints, object configurations, and embodiments. We present Canny-guided Robot Data Generation using Video Diffusion Transformers (CRAFT), a video diffusion-based framework for scalable bimanual demonstration generation that synthesizes temporally coherent manipulation videos while producing action labels.

## Related
<!-- [[other-paper-citekey]] -->
