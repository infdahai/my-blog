---
citekey: "wangEvoNavBenchBenchmarkingLifelongNavigationEvolvingEnvironments2026"
title: "EvoNav-Bench: Benchmarking Lifelong Navigation in Evolving Environments"
authors: ["Xilin Wang", "Guoxi Zhang", "Hongming Xu", "Zhuofan Zhang", "Tianxu Wang", "Lifeng Fan"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.08292"
doi: "10.48550/arXiv.2609.08292"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-11
---

# EvoNav-Bench: Benchmarking Lifelong Navigation in Evolving Environments

> Xilin Wang, Guoxi Zhang, Hongming Xu, Zhuofan Zhang, Tianxu Wang, Lifeng Fan · 2026
> [arXiv](https://arxiv.org/abs/2609.08292) · [PDF](https://arxiv.org/pdf/2609.08292)

## Abstract

Lifelong navigation (LN) requires an embodied agent to solve a sequence of navigation subtasks in the same environment. Since solving each subtask from scratch incurs redundant exploration, an LN agent must consolidate experience from earlier stages and reuse it in later stages, often through persistent scene representations such as scene graphs or visual snapshots. However, existing approaches typically assume a stationary environment, whereas in real-world LN settings, human activities can cause the environment to evolve. With the stationary assumption violated, existing methods may fuse outdated prior observations with new observations, yet current benchmarks cannot reveal this failure mode. In this paper, we present EvoNav-Bench, which extends the GOAT-Bench style LN formulation in the context of evolving environments. Built on the ProcTHOR framework, EvoNav-Bench introduces environment modifications between navigation tasks, making prior experience useful but not fully reliable. This design enables controlled evaluation of how environment evolution affects LN agents that reuse prior scene observations. Using EvoNav-Bench, we benchmark three recent methods that build and reuse scene representations for navigation. We also compare three simple heuristic strategies for handling environment evolution: Frontier-Update, Fail-then-Update, and Stage-Reset. Our results show that existing methods are brittle under environment evolution, while the heuristic strategies enable a controlled analysis of how agents can adapt to scene changes and mitigate their impact.

## TL;DR

Lifelong navigation (LN) requires an embodied agent to solve a sequence of navigation subtasks in the same environment. Since solving each subtask from scratch incurs redundant exploration, an LN agent must consolidate experience from earlier stages and reuse it in later stages, often through persistent scene representations such as scene graphs or visual snapshots.

## Related
<!-- [[other-paper-citekey]] -->
