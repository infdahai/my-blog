---
citekey: "huangBeyondSpatialBenchmarksSpatialReasoningNavigation2026"
title: "Beyond Spatial Benchmarks: From Spatial Reasoning to Navigation"
authors: ["Xun Huang", "Shijia Zhao", "Rongsheng Qu", "Jiayuan Li", "Xin Lu", "Weixin Li", "Chenglu Wen", "Cheng Wang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.29934"
doi: "10.48550/arXiv.2609.29934"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-26
---

# Beyond Spatial Benchmarks: From Spatial Reasoning to Navigation

> Xun Huang, Shijia Zhao, Rongsheng Qu, Jiayuan Li, Xin Lu, Weixin Li, Chenglu Wen, Cheng Wang · 2026
> [arXiv](https://arxiv.org/abs/2609.29934) · [PDF](https://arxiv.org/pdf/2609.29934)

## Abstract

Does progress on spatial reasoning benchmarks translate into better navigation? Existing benchmarks test isolated inferences from images or videos, with little connection to downstream navigation. Our analysis reveals a gap between benchmark-oriented spatial specialization and navigation performance, and shows how aligning spatial supervision with navigation goals, phases, and decision learning improves navigation. Guided by these findings, we build \textsc{Spatial-Nav-100K} and fine-tune in two stages, \textit{i.e.} first learning a shared spatial-navigation foundation, and then specializing each phase with the abilities it relies on. We further introduce Spatial-NPD, where a teacher conditioned on spatial priors produces grounded action preferences and distills them into a student policy, so no explicit spatial reasoning is needed at inference. With 45 A100 GPU-hours of policy training, our 8B model reaches SR/SPL of 77.4/35.4 on HM3D-v0.2, 60.2/30.5 on HM3D-v0.1, and 47.9/20.6 on train-unseen MP3D. It outperforms several systems that rely on closed-source models or thousands of GPU-hours of training, at 148 ms per action step. All code and datasets will be publicly available at https://github.com/ylwhxht/Spatial-Nav.

## TL;DR

Does progress on spatial reasoning benchmarks translate into better navigation? Existing benchmarks test isolated inferences from images or videos, with little connection to downstream navigation.

## Related
<!-- [[other-paper-citekey]] -->
