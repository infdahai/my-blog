---
citekey: "liuMotionForgeDataGenerationPipelineLargeScaleBenchmarkLong2026"
title: "MotionForge: A Data Generation Pipeline and Large-Scale Benchmark for Long-Horizon Manipulation of Dynamic Objects with Domain Shifts"
authors: ["Mohan Liu", "Dengchen Mei", "Haotian Xian", "Ruyang Han", "Jiayi Sun", "Xuanyu Chen", "Haitian Zhang", "Luxi Li", "Kaimin Mao", "Lin Wang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.25689"
doi: "10.48550/arXiv.2609.25689"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-23
---

# MotionForge: A Data Generation Pipeline and Large-Scale Benchmark for Long-Horizon Manipulation of Dynamic Objects with Domain Shifts

> Mohan Liu, Dengchen Mei, Haotian Xian, Ruyang Han, Jiayi Sun, Xuanyu Chen, Haitian Zhang, Luxi Li, Kaimin Mao, Lin Wang · 2026
> [arXiv](https://arxiv.org/abs/2609.25689) · [PDF](https://arxiv.org/pdf/2609.25689)

## Abstract

Recent advances in learning-based robot policies have demonstrated promising progress, yet they are predom- inantly evaluated in static or quasi-static environments. In dynamic manipulation, objects and scenes continuously evolve while the robot perceives, reasons, and acts. However, recent dynamic simulation benchmarks largely focus on short-horizon, reactive interactions with simple motion patterns and offer limited support for both systematic evaluation under domain shifts and model-agnostic real-time execution protocols. To bridge these gaps, we introduce MotionForge, the first large- scale simulation benchmark and data-generation pipeline tailored to jointly evaluate domain shifts and long-horizon interaction in dynamic manipulation. MotionForge comprises 40 dynamic interaction tasks spanning 11 distinct motion patterns, with dedicated support for 17 long-horizon tasks. Our benchmark introduces two key novelties: (1) a systematic evaluation protocol for assessing policy robustness under both single-factor (e.g., only backgrounds shift) and joint domain shifts (e.g., simultaneous shifts of objects, backgrounds, lighting, and speed); and (2) a decoupled, latency-aware execution protocol where the environ- ment continuously evolves independently of policy inference time. Extensive evaluations of representative general-purpose robot policies on our benchmark reveal substantial limitations under joint domain shifts. These findings expose a critical gap between current policy capabilities and the requirements of robust long- horizon manipulation of dynamic objects under domain shifts, establishing MotionForge as a comprehensive testbed for future research in embodied AI.

## TL;DR

Recent advances in learning-based robot policies have demonstrated promising progress, yet they are predom- inantly evaluated in static or quasi-static environments. In dynamic manipulation, objects and scenes continuously evolve while the robot perceives, reasons, and acts.

## Related
<!-- [[other-paper-citekey]] -->
