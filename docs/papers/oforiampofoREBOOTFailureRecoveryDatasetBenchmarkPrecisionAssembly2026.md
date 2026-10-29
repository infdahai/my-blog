---
citekey: "oforiampofoREBOOTFailureRecoveryDatasetBenchmarkPrecisionAssembly2026"
title: "REBOOT: From Failure to Recovery - A Dataset and Benchmark for Precision Assembly"
authors: ["Nana Yaw Owusu Ofori-Ampofo", "Samira Ebrahimi Kahou", "Joseph Thekinen"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.22591"
doi: "10.48550/arXiv.2609.22591"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-22
---

# REBOOT: From Failure to Recovery - A Dataset and Benchmark for Precision Assembly

> Nana Yaw Owusu Ofori-Ampofo, Samira Ebrahimi Kahou, Joseph Thekinen · 2026
> [arXiv](https://arxiv.org/abs/2609.22591) · [PDF](https://arxiv.org/pdf/2609.22591)

## Abstract

Robot learning policies fail in characteristic ways: they stall in uncertain states, drift during contact-rich alignment, and miss targets by millimetres in precision tasks. Yet training datasets consist largely of successful demonstrations, while real-world benchmarks often reduce performance to binary success. This limits both supervision for recovery and analysis of where failures occur. We introduce REBOOT (Recovery Episode Benchmark for Off-nominal Trajectories), the first robot manipulation benchmark designed around failure as a first-class signal. REBOOT contains 2,160 demonstrations across 18 precision assembly tasks, each decomposed into five shared phases: Align(pick), Engage(pick), Transport, Align(place), and Engage(place), enabling phase-level evaluation beyond terminal success. Failures are introduced across phases and paired with expert recovery trajectories that return the system to a valid continuation state. Tasks are annotated with rotational symmetry, engagement-clearance precision tier, and assembly direction through matched install-remove pairs. Failure episodes are labeled by phase and categorical failure mode, enabling attribution to kinematic stage and tolerance violation. Data includes synchronized RGB-D observations from four viewpoints and grounded natural-language descriptions of phase-level success and failure conditions. Half the dataset contains expert demonstrations; the other half contains recovery demonstrations sampled to reflect failures observed in imitation-learned policy rollouts. We benchmark action-chunked transformer, diffusion, and $π_0$-FAST policies using phase-level completion rates, revealing model-specific failure points hidden by binary evaluation. Dataset and code: https://nanayawoa.github.io/REBOOT

## TL;DR

Robot learning policies fail in characteristic ways: they stall in uncertain states, drift during contact-rich alignment, and miss targets by millimetres in precision tasks. Yet training datasets consist largely of successful demonstrations, while real-world benchmarks often reduce performance to binary success.

## Related
<!-- [[other-paper-citekey]] -->
