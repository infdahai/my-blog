---
citekey: "duOneInfinityActualizingFuturesPretrainedWorldModelsActions2026"
title: "One from Infinity: Actualizing Futures from Pretrained World Models into Robot Actions"
authors: ["Bang Du", "Yichen Xie", "Shuqi Zhao", "Yuxin Chen", "Menglin Wu", "Masayoshi Tomizuka"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.36413"
doi: "10.48550/arXiv.2609.36413"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# One from Infinity: Actualizing Futures from Pretrained World Models into Robot Actions

> Bang Du, Yichen Xie, Shuqi Zhao, Yuxin Chen, Menglin Wu, Masayoshi Tomizuka · 2026
> [arXiv](https://arxiv.org/abs/2609.36413) · [PDF](https://arxiv.org/pdf/2609.36413)

## Abstract

A pretrained video world model admits many plausible futures for a scene, but a robot must realize the exact task-conditioned one. To turn world models into executable robot policies, existing methods fine-tune the heavy world model backbone using large-scale robot data and computational resources. Challenging this status quo, we argue that the expensive part has already been paid in the world model pretraining since the representation space of a video world model lays out the diverse potential futures. In this case, what remains is to select the future that accomplishes the task and to read out the actions that realize it. We formalize this task as actualization, which learns a task-conditioned selection and realization on top of a prior supplied by a frozen world model. This can be solved by a tiny actualizer model. We implement RoboActualizer with as few as 60M parameters on top of a frozen world model encoder. The actualizer is composed of two lightweight DiT experts that jointly predict future latents and actions by flow matching. The model can be trained entirely on a single GPU with 32 GB peak memory. With up to 100x fewer trainable parameters than existing WAMs and VLAs, RoboActualizer reaches great performance on simulation benchmarks including LIBERO, LIBERO-Plus, RoboTwin 2.0 and five tasks on two real-world platforms, with a low latency of 39 ms that allows real-time control.

## TL;DR

A pretrained video world model admits many plausible futures for a scene, but a robot must realize the exact task-conditioned one. To turn world models into executable robot policies, existing methods fine-tune the heavy world model backbone using large-scale robot data and computational resources.

## Related
<!-- [[other-paper-citekey]] -->
