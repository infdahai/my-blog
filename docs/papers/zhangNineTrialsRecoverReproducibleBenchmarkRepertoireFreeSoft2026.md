---
citekey: "zhangNineTrialsRecoverReproducibleBenchmarkRepertoireFreeSoft2026"
title: "Nine Trials to Recover: A Reproducible Benchmark for Repertoire-Free Soft-Robot Damage Adaptation"
authors: ["Siyuan Zhang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.07616"
doi: "10.48550/arXiv.2610.07616"
tags: [paper, embodied-ai, "cs.RO", "cs.SY", "eess.SY"]
status: unread
rating:
created: 2026-10-08
---

# Nine Trials to Recover: A Reproducible Benchmark for Repertoire-Free Soft-Robot Damage Adaptation

> Siyuan Zhang · 2026
> [arXiv](https://arxiv.org/abs/2610.07616) · [PDF](https://arxiv.org/pdf/2610.07616)

## Abstract

We present a repertoire-free benchmark for soft-robot damage recovery under nine online trials. The protocol pairs damage masks within each morphology, retains a measured nominal fallback, and separates method development from evaluation on new bodies. A Gaussian-process expected-improvement (GP-EI) reference controller adapts actuator phases using three initialization probes and six feedback-selected rollouts. Across two disjoint 75-body cohorts, it outperforms random search, Sobol, CEM, and CMA-ES under equal budgets. GP-EI improves the worst-mask gain on 69/75 confirmation bodies and exceeds these four baselines by 0.235-0.310 mean worst-mask reward. A TuRBO-style local GP is the closest comparator; the paired confidence interval includes zero. Post-confirmation fixed-controller replay finds 5.06 voxel widths of mean recovery together with a 0.0031 increase in worst-mask p99 geometric edge strain; a strict no-added-demand deployment gate retains 48.7% of mean gain. In a frozen development stress test that physically removes 10% of occupied voxels, GP-EI improves 71/75 bodies and exceeds official BoTorch TuRBO by 0.356 mean worst-mask gain. Together, the replayable controllers, body-level inference, and frozen-cohort evaluation provide a reference for measuring the added value of learned damage priors and future adaptation methods.

## TL;DR

We present a repertoire-free benchmark for soft-robot damage recovery under nine online trials. The protocol pairs damage masks within each morphology, retains a measured nominal fallback, and separates method development from evaluation on new bodies.

## Related
<!-- [[other-paper-citekey]] -->
