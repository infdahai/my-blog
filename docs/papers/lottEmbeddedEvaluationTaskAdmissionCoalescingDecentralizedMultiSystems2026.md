---
citekey: "lottEmbeddedEvaluationTaskAdmissionCoalescingDecentralizedMultiSystems2026"
title: "Embedded Evaluation of Task Admission Coalescing in Decentralized Multi-Robot Systems"
authors: ["James Lott", "Vahraz Honary"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.09187"
doi: "10.48550/arXiv.2610.09187"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-08
---

# Embedded Evaluation of Task Admission Coalescing in Decentralized Multi-Robot Systems

> James Lott, Vahraz Honary · 2026
> [arXiv](https://arxiv.org/abs/2610.09187) · [PDF](https://arxiv.org/pdf/2610.09187)

## Abstract

Multi-robot task allocators in dynamic missions commonly admit newly released tasks immediately, potentially invoking allocation for each new arrival. We evaluate task-admission coalescing as a mechanism for controlling allocator processor work while accounting for target-service latency, using CBAA, ACBBA, PI, and HIPC as a representative MRTA suite. The study comprises a 3,000-mission AGX Orin campaign with measured computation delay, 3,000 paired zero-compute missions, and a 96-mission Pololu 3pi+ RP2040 allocator hardware-in-the-loop campaign. Immediate (Eager) admission is compared with thresholds of two, four, and eight tasks and a four-task policy with a 10-s waiting bound across three arrival rates. Across the AGX experiments, coalescing reduces both allocator calls and processor work in 31 of 48 evaluated conditions, although the magnitude of the saving varies by allocator. The principal cost appears under sparse arrivals, where four-task batching increases online-target mean latency by 20.08-23.57 s, predominantly through admission waiting. Bounded admission reduces mean work in ten of twelve allocator-load conditions, including a 19.35% reduction with a 1.40-s mean latency increase for high-arrival HIPC. RP2040 experiments show that this tradeoff can become more favorable as processor constraints tighten. Across four matched medium-arrival HIPC scenarios, Count b=4 reduces mean RP2040 work by 59.85% and service latency by 39.47%, while the corresponding AGX cases increase latency by 27.69%. These results show that the usefulness of task-admission coalescing depends on arrival intensity, allocator-specific behavior, and the relative cost of computation on the execution platform.

## TL;DR

Multi-robot task allocators in dynamic missions commonly admit newly released tasks immediately, potentially invoking allocation for each new arrival. We evaluate task-admission coalescing as a mechanism for controlling allocator processor work while accounting for target-service latency, using CBAA, ACBBA, PI, and HIPC as a representative MRTA suite.

## Related
<!-- [[other-paper-citekey]] -->
