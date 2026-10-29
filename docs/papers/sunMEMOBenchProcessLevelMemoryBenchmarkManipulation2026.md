---
citekey: "sunMEMOBenchProcessLevelMemoryBenchmarkManipulation2026"
title: "MEMOBench: A Process Level Memory Benchmark for Robotic Manipulation"
authors: ["Haiyang Sun", "Haoxiao Wang", "Junming Chen", "Weicheng Fang", "Zihao Su", "Jingkun Yi", "Wenyou Yi", "Hao Chen", "Zhou Zhao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.07047"
doi: "10.48550/arXiv.2609.07047"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-09-11
---

# MEMOBench: A Process Level Memory Benchmark for Robotic Manipulation

> Haiyang Sun, Haoxiao Wang, Junming Chen, Weicheng Fang, Zihao Su, Jingkun Yi, Wenyou Yi, Hao Chen, Zhou Zhao · 2026
> [arXiv](https://arxiv.org/abs/2609.07047) · [PDF](https://arxiv.org/pdf/2609.07047)

## Abstract

Robotic manipulation often requires acting on information that is no longer visible, yet Vision-Language-Action policies are usually evaluated when the current observation largely determines the next action. Existing robotic memory benchmarks expose this gap, but they still rely mainly on final task success and therefore conflate forgetting with manipulation failure. We present \textbf{MEMOBench}, a benchmark for process level memory evaluation in robotic manipulation. MEMOBench includes 30 history dependent tasks, 1{,}500 expert demonstrations, and 4{,}200 executable checkpoint instances from 84 templates. Each checkpoint pairs coarse to fine language with a simulator predicate and labels one memory operation: Storage, Update, or Compression. These annotations define Memory Storage Rate, Memory Update Rate, and Memory Compression Rate, which measure memory fidelity alongside task success. Across standard and memory augmented VLA policies, the strongest memory module baseline reaches only 31.9\% average success rate, and high storage often coexists with weak update and compression. Checkpoint language also supervises semantic, contrastive, and framewise memory alignment objectives, yielding modest gains across different memory operations. MEMOBench provides a diagnostic evaluation suite and training supervision for memory grounded robotic policies. The project page is available at https://github.com/Collab-Gen/MEMOBench.

## TL;DR

Robotic manipulation often requires acting on information that is no longer visible, yet Vision-Language-Action policies are usually evaluated when the current observation largely determines the next action. Existing robotic memory benchmarks expose this gap, but they still rely mainly on final task success and therefore conflate forgetting with manipulation failure.

## Related
<!-- [[other-paper-citekey]] -->
