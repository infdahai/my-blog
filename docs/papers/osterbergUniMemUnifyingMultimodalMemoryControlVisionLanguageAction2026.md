---
citekey: "osterbergUniMemUnifyingMultimodalMemoryControlVisionLanguageAction2026"
title: "UniMem: Unifying Multimodal Memory and Control for Vision-Language-Action Models"
authors: ["Lars Osterberg", "Maggie Wang", "Mac Schwager"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.22869"
doi: "10.48550/arXiv.2608.22869"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-08-26
---

# UniMem: Unifying Multimodal Memory and Control for Vision-Language-Action Models

> Lars Osterberg, Maggie Wang, Mac Schwager · 2026
> [arXiv](https://arxiv.org/abs/2608.22869) · [PDF](https://arxiv.org/pdf/2608.22869)

## Abstract

While Vision-Language-Action (VLA) models have leveraged internet-scale pretraining and task-focused finetuning to achieve strong performance on long-horizon tasks, they often struggle with non-Markovian tasks that require memory. Existing approaches to memory typically involve additional Vision-Language-Models (VLMs) for long-term memory management, introducing a memory bottleneck and a fractured training pipeline. Conditioning on multiple historical frames can provide the VLA with access to more descriptive features of past scenes, but can degrade performance if frames are chosen at arbitrary, fixed intervals. To address these limitations, we present UniMem, a framework that unifies high-level, multimodal memory and low-level control under one backbone. UniMem employs an event classifier for memory updates, a keyframe encoder for dense spatial memory, and a keyframe caching technique to minimize overhead during policy rollouts. We evaluate UniMem across five simulation and four hardware tasks targeting sequential and spatial memory, demonstrating that our unified, single-model system outperforms fixed-interval image sampling baselines (93.4% vs. 68.2%) in simulation and hierarchical baselines (80.0% vs. 43.5%) in hardware, while offering faster inference and a simple training pipeline for easy adoption. Project website: https://losterberg3.github.io/unimem-vla/

## TL;DR

While Vision-Language-Action (VLA) models have leveraged internet-scale pretraining and task-focused finetuning to achieve strong performance on long-horizon tasks, they often struggle with non-Markovian tasks that require memory. Existing approaches to memory typically involve additional Vision-Language-Models (VLMs) for long-term memory management, introducing a memory bottleneck and a fractured training pipeline.

## Related
<!-- [[other-paper-citekey]] -->
