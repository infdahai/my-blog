---
citekey: "chenNotAllUncertaintyMattersSimulationLoopFastSlow2026"
title: "Not All Uncertainty Matters: Simulation-in-the-Loop Fast-Slow Reasoning for Decision-Critical Autonomous Driving System"
authors: ["Jiayi Chen", "Shuai Wang", "Guangxu Zhu", "Derrick Wing Kwan Ng", "Chengzhong Xu", "Kaibin Huang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.09520"
doi: "10.48550/arXiv.2610.09520"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-10-10
---

# Not All Uncertainty Matters: Simulation-in-the-Loop Fast-Slow Reasoning for Decision-Critical Autonomous Driving System

> Jiayi Chen, Shuai Wang, Guangxu Zhu, Derrick Wing Kwan Ng, Chengzhong Xu, Kaibin Huang · 2026
> [arXiv](https://arxiv.org/abs/2610.09520) · [PDF](https://arxiv.org/pdf/2610.09520)

## Abstract

Large vision-language models (VLMs) provide powerful open-world perception and reasoning for autonomous driving, but their high computational cost and inference latency make continuous cloud-side use impractical. This motivates fast--slow collaboration, where efficient onboard modules handle real-time perception and control while cloud models provide high-level reasoning only when needed. The key challenge is deciding when cloud reasoning should influence time-critical driving decisions. Existing methods often rely on perception uncertainty, heuristic triggers, or resource-driven policies, without assessing whether resolving an uncertainty will improve planning. We propose \textbf{SIGMA}, a simulation-in-the-loop framework for task-oriented fast--slow collaboration. SIGMA embeds the planner into uncertainty assessment and evaluates how plausible scene realizations under semantic and geometric uncertainty affect feasible trajectories and planning cost. Based on these outcomes, it estimates the expected reduction in planning cost from resolving uncertainty. We further introduce expected planning gain (EPG), a decision-level metric for cloud invocation, cloud-guidance integration, and request prioritization under deadline and resource constraints. Experiments in CARLA show that SIGMA reduces unnecessary cloud interactions while improving planning, efficiency, and navigation success in static and dynamic obstacle scenarios. Compared with fixed-period collaboration, SIGMA reduces unnecessary cloud interactions by 50\%, improves navigation success by more than 6\%, and cuts finish time by up to 26.2\% in dynamic scenarios.

## TL;DR

Large vision-language models (VLMs) provide powerful open-world perception and reasoning for autonomous driving, but their high computational cost and inference latency make continuous cloud-side use impractical. This motivates fast--slow collaboration, where efficient onboard modules handle real-time perception and control while cloud models provide high-level reasoning only when needed.

## Related
<!-- [[other-paper-citekey]] -->
