---
citekey: "liuLANTERNClosedLoopBenchmarkVLMBasedCooperativeDriving2026"
title: "LANTERN: A Closed-Loop Benchmark for VLM-Based Cooperative Driving with Temporally Grounded Warnings"
authors: ["Yongshuo Liu", "Xu Gao", "Morui Zhu", "Yongqi Zhu", "Qi Chen", "Deyuan Qu", "Song Fu", "Qing Yang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.06368"
doi: "10.48550/arXiv.2609.06368"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-11
---

# LANTERN: A Closed-Loop Benchmark for VLM-Based Cooperative Driving with Temporally Grounded Warnings

> Yongshuo Liu, Xu Gao, Morui Zhu, Yongqi Zhu, Qi Chen, Deyuan Qu, Song Fu, Qing Yang · 2026
> [arXiv](https://arxiv.org/abs/2609.06368) · [PDF](https://arxiv.org/pdf/2609.06368)

## Abstract

We present LANTERN, a closed-loop benchmark for temporally grounded cooperative warnings. LANTERN separates warning onset, hazard onset, warning termination, and post-hazard recovery, and evaluates each physical event under matched warning and no-warning executions so that the warning's contribution is measured in isolation rather than confounded with onboard vision. The benchmark spans six safety-critical scenario families and provides 3,272 sequences with 236,309 frames for training, together with 120 matched route pairs for closed-loop evaluation. Each hazard route is evaluated under the warning and no-warning conditions, while its no-hazard control penalizes unconditional braking. We further introduce the Cooperative Unified Score (CUS), a safety-gated metric that jointly rewards route progress, anticipation, clearance, and recovery. Fine-tuning a representative VLM driving model raises CUS from 34.6 without warnings to 75.5 with them, demonstrating both the value of cooperative warnings and the discriminative power of the paired protocol. All resources will be made publicly available.

## TL;DR

We present LANTERN, a closed-loop benchmark for temporally grounded cooperative warnings. LANTERN separates warning onset, hazard onset, warning termination, and post-hazard recovery, and evaluates each physical event under matched warning and no-warning executions so that the warning's contribution is measured in isolation rather than confounded with onboard vision.

## Related
<!-- [[other-paper-citekey]] -->
