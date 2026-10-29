---
citekey: "yuHIDRAHierarchicalDualRoutingAttentionReplayFreeLifelong2026"
title: "HIDRA: Hierarchical Dual-Routing Attention for Replay-Free Lifelong Imitation Learning"
authors: ["Fanqi Yu", "Matteo Tiezzi", "Cigdem Beyan", "Tommaso Apicella", "Vittorio Murino"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.36374"
doi: "10.48550/arXiv.2610.36374"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-10-29
---

# HIDRA: Hierarchical Dual-Routing Attention for Replay-Free Lifelong Imitation Learning

> Fanqi Yu, Matteo Tiezzi, Cigdem Beyan, Tommaso Apicella, Vittorio Murino · 2026
> [arXiv](https://arxiv.org/abs/2610.36374) · [PDF](https://arxiv.org/pdf/2610.36374)

## Abstract

Robotic agents operating in real-world environments must adapt continuously from a stream of multimodal demonstrations, often under constraints that preclude storing or revisiting past data. In this replay-free, single-pass lifelong imitation learning setting, sequential updates can progressively distort the representation space, making expert-based approaches particularly sensitive to routing interference, causing expert selection to degrade over time. We propose HIDRA, a structured routing framework that mitigates this issue through a hierarchical dual-attention mechanism, which decouples instruction-level expert retrieval from context-dependent refinement. To further stabilize routing under representation drift, HIDRA introduces a key-level geometric regularization that enforces both alignment within tasks and separation across tasks. The resulting approach enables reliable expert selection while supporting an expandable set of experts for continual adaptation. We evaluate HIDRA on several LIBERO benchmark suites, including more challenging variants with heterogeneous task sequences and paraphrased language instructions. Our approach consistently outperforms both replay-free and replay-based baselines, improving AUC and forward transfer while maintaining low forgetting, with stronger gains under high interference and language variation. The code is available at: https://github.com/yfqi/HIDRA.

## TL;DR

Robotic agents operating in real-world environments must adapt continuously from a stream of multimodal demonstrations, often under constraints that preclude storing or revisiting past data. In this replay-free, single-pass lifelong imitation learning setting, sequential updates can progressively distort the representation space, making expert-based approaches particularly sensitive to routing interference, causing expert selection to degrade over time.

## Related
<!-- [[other-paper-citekey]] -->
