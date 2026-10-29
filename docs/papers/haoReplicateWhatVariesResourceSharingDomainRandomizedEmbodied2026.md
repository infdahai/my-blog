---
citekey: "haoReplicateWhatVariesResourceSharingDomainRandomizedEmbodied2026"
title: "Replicate What Varies: Resource Sharing for Domain-Randomized Embodied Simulation"
authors: ["Zixu Hao", "Weijun Wang", "Xiangyu Li", "Liang Mi", "Hao Wu", "Yunxin Liu", "Ting Cao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.33582"
doi: "10.48550/arXiv.2610.33582"
tags: [paper, embodied-ai, "cs.AI", "cs.DC", "cs.RO"]
status: unread
rating:
created: 2026-10-28
---

# Replicate What Varies: Resource Sharing for Domain-Randomized Embodied Simulation

> Zixu Hao, Weijun Wang, Xiangyu Li, Liang Mi, Hao Wu, Yunxin Liu, Ting Cao · 2026
> [arXiv](https://arxiv.org/abs/2610.33582) · [PDF](https://arxiv.org/pdf/2610.33582)

## Abstract

Simulation provides a low-cost sandbox where embodied agents can attempt tasks, observe outcomes, and learn from experience. Running many diverse simulation environments concurrently can consume substantial CPU and GPU memory because independently constructed scenes duplicate resources that remain unchanged across instances. We present Patchwork, a resource-sharing system for domain-randomized simulation, built around the representation $E=T+Δ$: a shared template contains common resources, and a patch records the mutations needed to construct a target environment. Patchwork separates randomization sampling from replay and selects reusable templates together with patches that preserve each target environment's intended configuration. Its layered runtime shares compiled model structure and immutable assets while keeping mutable parameters and simulation state private to each instance. We implement Patchwork on robosuite and MuJoCo and evaluate it on LIBERO-plus and RoboCasa365 workloads. At 32 replicas, shared-template execution reduces CPU RSS by 88-92% relative to process-per-environment execution. Controlled experiments show how sharing shifts memory growth toward template diversity and unique asset content rather than instance count, within the supported sharing boundaries.

## TL;DR

Simulation provides a low-cost sandbox where embodied agents can attempt tasks, observe outcomes, and learn from experience. Running many diverse simulation environments concurrently can consume substantial CPU and GPU memory because independently constructed scenes duplicate resources that remain unchanged across instances.

## Related
<!-- [[other-paper-citekey]] -->
