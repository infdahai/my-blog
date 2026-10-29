---
citekey: "kimOdysseyClosedLoopBenchmarkLongHorizonRealWorld2026"
title: "Odyssey: A Closed-Loop Benchmark for Long-Horizon Real-World Driving with Explicit Navigation Routes"
authors: ["Jungho Kim", "Hongjae Shin", "Seunghoon Yu", "Heecheol Yoo", "Myeongjun Kim", "Jiyong Oh", "Donghyuk Kwak", "Seunghyeop Nam", "Haesung Oh", "Hyunju Kim", "Hyungchan Cho", "Jaehyun Park", "Soo Won Seo", "Jun Won Choi"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.06469"
doi: "10.48550/arXiv.2610.06469"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-10-07
---

# Odyssey: A Closed-Loop Benchmark for Long-Horizon Real-World Driving with Explicit Navigation Routes

> Jungho Kim, Hongjae Shin, Seunghoon Yu, Heecheol Yoo, Myeongjun Kim, Jiyong Oh, Donghyuk Kwak, Seunghyeop Nam, Haesung Oh, Hyunju Kim, Hyungchan Cho, Jaehyun Park, Soo Won Seo, Jun Won Choi · 2026
> [arXiv](https://arxiv.org/abs/2610.06469) · [PDF](https://arxiv.org/pdf/2610.06469)

## Abstract

Closed-loop evaluation of end-to-end driving requires continuous rollouts that reveal how earlier decisions affect subsequent driving. However, existing benchmarks evaluate only short segments and fail to capture later consequences. Ambiguous directional commands also obscure the intended navigation objective. We introduce Odyssey, a closed-loop benchmark for long-horizon driving comprising 100 scenarios, each reconstructed from a 100-second nuPlan driving log to preserve the context of navigation maneuvers and traffic interactions. To provide a consistent navigation objective, Odyssey replaces directional commands with explicit standard-definition (SD) map routes that specify which roads to follow, while sensor-based planning determines local driving actions. Throughout these rollouts, diffusion-based refinement of 3DGS-rendered images reduces rendering artifacts along the ego trajectory. To assess how effectively planners follow these routes and prepare for upcoming maneuvers, we introduce SD Route Compliance and Pre-Lane Change Score. These assessments are complemented by RouteDS, which extends the Driving Score with penalties for SD-route deviations and failed lane preparation. We adapt state-of-the-art planners, including vision-language-action (VLA) models, and evaluate their navigation performance using these metrics. Odyssey highlights open questions in route representation and integration for E2E driving. Benchmark code and adapted baselines will be released publicly.

## TL;DR

Closed-loop evaluation of end-to-end driving requires continuous rollouts that reveal how earlier decisions affect subsequent driving. However, existing benchmarks evaluate only short segments and fail to capture later consequences.

## Related
<!-- [[other-paper-citekey]] -->
