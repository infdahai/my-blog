---
citekey: "kimComplementaryFutureTokenPruningWorldActionModels2026"
title: "Complementary Future Token Pruning for World Action Models"
authors: ["Baekseung Kim", "Junhoo Lee", "Sohyeon Hong", "Suhyun Jeon", "Minkyu Kim", "Seungyeon Kim", "Donghoon Han", "Nojun Kwak"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.19957"
doi: "10.48550/arXiv.2610.19957"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-16
---

# Complementary Future Token Pruning for World Action Models

> Baekseung Kim, Junhoo Lee, Sohyeon Hong, Suhyun Jeon, Minkyu Kim, Seungyeon Kim, Donghoon Han, Nojun Kwak · 2026
> [arXiv](https://arxiv.org/abs/2610.19957) · [PDF](https://arxiv.org/pdf/2610.19957)

## Abstract

World action models (WAMs) jointly predict future visual states and robot actions, but processing dense future-frame tokens incurs substantial inference latency. We propose CF-Prune, a training-free framework for pruning future-frame tokens in pretrained WAMs. Our key insight is that future visual predictions support action generation and therefore need not preserve every visual detail required for high-fidelity video synthesis. CF-Prune combines instruction and action attention to identify task-relevant tokens during the initial denoising forward pass, even when future-frame and action representations remain highly noisy. An entropy-based phase identification mechanism further retains dense computation during precision phases to mitigate pruning-induced performance degradation. Experiments on RoboLab, RoboCasa, and real-world manipulation tasks demonstrate consistent inference speedups. At a 35% pruning ratio, CF-Prune achieves average speedups of 1.19-1.27x while improving task success rates. At a 50% pruning ratio, it achieves 1.29-1.33x average speedups on both simulation benchmarks, with overall success rates within 1.0 percentage point of the baseline.

## TL;DR

World action models (WAMs) jointly predict future visual states and robot actions, but processing dense future-frame tokens incurs substantial inference latency. We propose CF-Prune, a training-free framework for pruning future-frame tokens in pretrained WAMs.

## Related
<!-- [[other-paper-citekey]] -->
