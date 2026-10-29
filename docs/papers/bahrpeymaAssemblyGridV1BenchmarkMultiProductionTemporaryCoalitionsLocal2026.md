---
citekey: "bahrpeymaAssemblyGridV1BenchmarkMultiProductionTemporaryCoalitionsLocal2026"
title: "AssemblyGrid v1: A Benchmark for Multi-Robot Production with Temporary Coalitions, Local Information, and Geometric Constraints"
authors: ["Fouad Bahrpeyma", "David Heik", "Dirk Reichelt"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.16075"
doi: "10.48550/arXiv.2609.16075"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-09-16
---

# AssemblyGrid v1: A Benchmark for Multi-Robot Production with Temporary Coalitions, Local Information, and Geometric Constraints

> Fouad Bahrpeyma, David Heik, Dirk Reichelt · 2026
> [arXiv](https://arxiv.org/abs/2609.16075) · [PDF](https://arxiv.org/pdf/2609.16075)

## Abstract

Flexible robotic production requires joint decisions on process progression, material routing, resource assignment, temporary cooperation, and simultaneous execution, since each decision can affect the feasibility of the others. The challenge is greater under decentralized control, where each robot acts from bounded local information while system progress depends on collective decisions, shared resources, material state, and workspace compatibility. These properties closely match cooperative multi-agent decision making under partial observability and resource contention. This paper introduces AssemblyGrid v1, a reproducible benchmark for repeated multi-robot production that combines explicit process progression, decentralized observations, material transfer, temporary multi-robot coalitions, productive concurrency, and geometry-dependent feasibility within one task-level formulation. The benchmark includes Flow, Coalition, and Concurrency workload families, each with three scenario levels. Task success and evaluation measures are defined independently of learning reward and solution method, allowing learning-based and non-learning methods to address the same production problem. AssemblyGrid v1 is evaluated through executable conformance checks, mechanism studies, and algorithmic experiments using a privileged centralized reference, structured decentralized controllers, and MARL methods including IPPO, MAPPO, and QMIX. Results demonstrate productive execution under centralized and decentralized control. The MARL experiments further show that decentralized policies can learn effective production behavior from local observations and actions, supporting AssemblyGrid as a controlled benchmark for studying cooperative decision making in flexible robotic production.

## TL;DR

Flexible robotic production requires joint decisions on process progression, material routing, resource assignment, temporary cooperation, and simultaneous execution, since each decision can affect the feasibility of the others. The challenge is greater under decentralized control, where each robot acts from bounded local information while system progress depends on collective decisions, shared resources, material state, and workspace compatibility.

## Related
<!-- [[other-paper-citekey]] -->
