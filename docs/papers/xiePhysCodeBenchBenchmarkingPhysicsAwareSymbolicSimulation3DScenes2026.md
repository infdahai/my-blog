---
citekey: "xiePhysCodeBenchBenchmarkingPhysicsAwareSymbolicSimulation3DScenes2026"
title: "PhysCodeBench: Benchmarking Physics-Aware Symbolic Simulation of 3D Scenes via Self-Corrective Multi-Agent Refinement"
authors: ["Tianyidan Xie", "Peiyu Wang", "Hu Jiaxin", "Yuyi Qian", "Yuxuan Wang", "Shenyi Wang", "Rui Ma", "Yanlun Peng", "Lanjun Wang", "Ying Tai", "Jian Yang", "Zili Yi"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2604.23580"
doi: "10.48550/arXiv.2604.23580"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-09-15
---

# PhysCodeBench: Benchmarking Physics-Aware Symbolic Simulation of 3D Scenes via Self-Corrective Multi-Agent Refinement

> Tianyidan Xie, Peiyu Wang, Hu Jiaxin, Yuyi Qian, Yuxuan Wang, Shenyi Wang, Rui Ma, Yanlun Peng, Lanjun Wang, Ying Tai, Jian Yang, Zili Yi · 2026
> [arXiv](https://arxiv.org/abs/2604.23580) · [PDF](https://arxiv.org/pdf/2604.23580)

## Abstract

Translating natural-language descriptions of physical phenomena into executable simulation code requires both programming expertise and physical reasoning. Current large language models (LLMs) lack this combination: they frequently produce code that runs but simulates the wrong physics. We introduce PhysCodeBench, the first benchmark for this task, with 1,200 expert-validated examples spanning four physical domains. Its evaluation suite, PhysCodeEval, goes beyond executability and visual fidelity to measure physical correctness directly from the engine state via conservation-law residuals and expert-written assertions, and supports cross-engine evaluation to disentangle physics reasoning from API fluency. As a reference method, we propose the Self-Corrective Multi-Agent Refinement Framework (SMRF), which decouples physics-aware error correction from code generation through specialized agents. This design is motivated by our finding that targeted correction, rather than generic iterative refinement, is the key driver of physical accuracy. SMRF nearly triples the physical-assertion pass rate of the best proprietary baseline (70.6\% vs.\ 23.8\%) and retains its advantage under cross-engine transfer.

## TL;DR

Translating natural-language descriptions of physical phenomena into executable simulation code requires both programming expertise and physical reasoning. Current large language models (LLMs) lack this combination: they frequently produce code that runs but simulates the wrong physics.

## Related
<!-- [[other-paper-citekey]] -->
