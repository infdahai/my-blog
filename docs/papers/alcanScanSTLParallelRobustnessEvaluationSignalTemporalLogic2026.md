---
citekey: "alcanScanSTLParallelRobustnessEvaluationSignalTemporalLogic2026"
title: "ScanSTL: Parallel Robustness Evaluation for Signal Temporal Logic"
authors: ["Gokhan Alcan"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.07346"
doi: "10.48550/arXiv.2610.07346"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-08
---

# ScanSTL: Parallel Robustness Evaluation for Signal Temporal Logic

> Gokhan Alcan · 2026
> [arXiv](https://arxiv.org/abs/2610.07346) · [PDF](https://arxiv.org/pdf/2610.07346)

## Abstract

Repeated evaluation and differentiation of Signal Temporal Logic (STL) robustness can become a computational bottleneck in robot planning and control. Sequential temporal recurrences limit parallelism, while dense masking increases memory requirements. We propose ScanSTL, which combines associative temporal aggregation with parallel scans and ordered block reductions. Eventually and Always use range extrema, while inclusive strong Until composes compact segment representations. A common range engine handles bounded and shifted intervals, including the guards required before delayed Until witnesses. Each exact temporal operator computes complete robustness traces with linear work and storage and logarithmic parallel depth on uniformly sampled finite signals. An open source JAX implementation supports automatic differentiation, batching, and compilation. We compare ScanSTL with STLCG and STLCG++ using CPU and GPU operator benchmarks and nine composed specifications. Across these nine specifications at 512 samples, ScanSTL achieves geometric mean speedups of 243 times for forward evaluation and 104 times for gradient computation over STLCG++ in JAX on the CPU. On an RTX~5090 GPU, ScanSTL evaluates unbounded Until over more than two million samples with median times below 0.1 ms for forward evaluation and 0.25 ms for gradient computation. Simulated escort and patrol experiments with a robot dog further demonstrate faster repair of violating plans and greater solver capacity in model predictive control.

## TL;DR

Repeated evaluation and differentiation of Signal Temporal Logic (STL) robustness can become a computational bottleneck in robot planning and control. Sequential temporal recurrences limit parallelism, while dense masking increases memory requirements.

## Related
<!-- [[other-paper-citekey]] -->
