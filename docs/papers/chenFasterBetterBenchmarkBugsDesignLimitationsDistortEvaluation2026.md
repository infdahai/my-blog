---
citekey: "chenFasterBetterBenchmarkBugsDesignLimitationsDistortEvaluation2026"
title: "Faster and Better? Benchmark Bugs and Design Limitations Distort the Evaluation of Vision-Language-Action Acceleration"
authors: ["Qiwei Chen", "Kaijun Zhou", "Nuohui Shi", "Zhiyang Li", "Yuxuan Feng", "Jinyu Gu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.37771"
doi: "10.48550/arXiv.2609.37771"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-04
---

# Faster and Better? Benchmark Bugs and Design Limitations Distort the Evaluation of Vision-Language-Action Acceleration

> Qiwei Chen, Kaijun Zhou, Nuohui Shi, Zhiyang Li, Yuxuan Feng, Jinyu Gu · 2026
> [arXiv](https://arxiv.org/abs/2609.37771) · [PDF](https://arxiv.org/pdf/2609.37771)

## Abstract

Simulated manipulation benchmarks are the standard tool for evaluating vision-language-action (VLA) policies and the acceleration methods that reduce their inference latency for on-robot deployment. On these benchmarks, we observe that some training-free acceleration methods, which approximate the baseline policy's computation, achieve higher measured success rates than the baseline itself. Success rates alone cannot establish whether such gains come from better task execution or from evaluation flaws. We therefore investigate two kinds of benchmark flaws behind these gains: bugs, where the implementation does not match the intended task or evaluation protocol, and design limitations, where success criteria and simulation settings do not fully capture how acceleration affects task execution. Starting from tasks with anomalous gains, we localize root causes by plotting object trajectories against checker acceptance regions, and classify the resulting bugs into task consistency, initialization, and reproducibility. Extending this audit to seven benchmarks, including RoboTwin, LIBERO-Plus, and VLABench, we identify 22 bugs of these types and 4 design limitations. For the latter, we revise permissive success checkers, correct unrealistic object masses, and add a motion-aware score that favors smoother actions. Experiments show that bug fixes can reverse method rankings, moving the baseline from last to first on one task. Addressing design limitations can likewise remove anomalous gains: on another task, the baseline moves from 21 percentage points behind an accelerated method to 5 points ahead. Gains attributed to acceleration can therefore be artifacts of the benchmark rather than better task execution. We release our bug fixes and revised benchmark settings to support trustworthy evaluation of VLA acceleration.

## TL;DR

Simulated manipulation benchmarks are the standard tool for evaluating vision-language-action (VLA) policies and the acceleration methods that reduce their inference latency for on-robot deployment. On these benchmarks, we observe that some training-free acceleration methods, which approximate the baseline policy's computation, achieve higher measured success rates than the baseline itself.

## Related
<!-- [[other-paper-citekey]] -->
