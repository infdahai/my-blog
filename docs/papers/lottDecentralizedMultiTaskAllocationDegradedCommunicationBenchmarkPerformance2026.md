---
citekey: "lottDecentralizedMultiTaskAllocationDegradedCommunicationBenchmarkPerformance2026"
title: "Decentralized Multi-Robot Task Allocation Under Degraded Communication: A Benchmark of Performance, Reliability, and Computation"
authors: ["James Lott", "Vahraz Honary"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.13711"
doi: "10.48550/arXiv.2609.13711"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-16
---

# Decentralized Multi-Robot Task Allocation Under Degraded Communication: A Benchmark of Performance, Reliability, and Computation

> James Lott, Vahraz Honary · 2026
> [arXiv](https://arxiv.org/abs/2609.13711) · [PDF](https://arxiv.org/pdf/2609.13711)

## Abstract

Selecting a decentralized Multi-Robot Task Allocation (MRTA) method for embedded deployment on autonomous platforms requires considering more than route performance alone. We benchmark six decentralized MRTA allocators (CBAA, ACBBA, PI, HIPC, DMCHBA, and DGA) in the Collaborative Visit (CV) scenario to characterize tradeoffs among MinMax and MinSum travel, communication robustness and demand, allocation reliability, computational burden, and scale sensitivity. The core study uses 500 paired ten-target instances across 25 ideal and degraded communication conditions spanning Bernoulli loss, Gilbert--Elliott loss, and Rayleigh fading, with additional campaigns examining pre-allocation, execution-integrated computation, and sensitivity to grid size, robot density, and target load. Across the 24 impaired core conditions, DGA and DMCHBA achieved the lowest mean MinMax travel at 24.49 and 24.78 steps, respectively. HIPC narrowly led mean MinSum travel at 66.95 steps, followed by DGA at 67.22, with both methods occupying the top two in every impaired condition. DMCHBA had the lowest publication intensity at 2.08 publications per team step. In ten-target pre-allocation, HIPC and DMCHBA remained viable and stable in every tested condition, while ACBBA, PI, and DGA lost stability or viability as communication degraded. Under ideal delivery, median full-protocol computation $\Cterm$ in the primary ten-target comparison ranged from 4.88 ms for DMCHBA to 1.346 s for DGA. Static route quality preserved DGA and DMCHBA as the leading MinMax methods, while DGA led MinSum at three of four target loads and HIPC led at 50 targets. Static and execution-integrated computation rankings diverged as task load increased. The results identify distinct allocator operating regions across route objective, communication behavior, reliability, and computational constraints.

## TL;DR

Selecting a decentralized Multi-Robot Task Allocation (MRTA) method for embedded deployment on autonomous platforms requires considering more than route performance alone. We benchmark six decentralized MRTA allocators (CBAA, ACBBA, PI, HIPC, DMCHBA, and DGA) in the Collaborative Visit (CV) scenario to characterize tradeoffs among MinMax and MinSum travel, communication robustness and demand, allocation reliability, computational burden, and scale sensitivity.

## Related
<!-- [[other-paper-citekey]] -->
