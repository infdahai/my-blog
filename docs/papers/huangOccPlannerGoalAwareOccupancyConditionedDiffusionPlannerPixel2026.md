---
citekey: "huangOccPlannerGoalAwareOccupancyConditionedDiffusionPlannerPixel2026"
title: "OccPlanner: Goal-Aware Occupancy-Conditioned Diffusion Planner for Pixel-Goal Navigation"
authors: ["Binling Huang", "Nianjin Ye", "Xi Yang", "Liang Hu", "Zhou Huang", "Shuang Wei", "Longrui Yang", "Yanchi Chen", "Lanpeng Jia"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.14160"
doi: "10.48550/arXiv.2608.14160"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-07
---

# OccPlanner: Goal-Aware Occupancy-Conditioned Diffusion Planner for Pixel-Goal Navigation

> Binling Huang, Nianjin Ye, Xi Yang, Liang Hu, Zhou Huang, Shuang Wei, Longrui Yang, Yanchi Chen, Lanpeng Jia · 2026
> [arXiv](https://arxiv.org/abs/2608.14160) · [PDF](https://arxiv.org/pdf/2608.14160)

## Abstract

Pixel-goal navigation specifies targets directly in the agent's camera view, but a target pixel provides neither metric depth nor traversability, making 3D goal grounding and collision-free continuous planning challenging. We present OccPlanner, a goal-aware occupancy-conditioned diffusion planner that grounds pixel goals in egocentric metric space and sequentially conditions the goal representation on temporal visual context and learned local 3D occupancy features. To provide occupancy supervision at scale, we introduce L3ROcc, which converts monocular RGB navigation videos into robot-centric local 3D occupancy annotations through geometric reconstruction and ray-based visibility reasoning. We train OccPlanner on InternData-N1 and evaluate it in closed-loop simulation across four unseen scene categories from InternScenes and two goal-distance ranges. In the 5-8 m setting, OccPlanner increases the average success rate (SR) over NavDP from 20.81% to 71.55% across the four categories, reaching 86.20% and 84.92% in cluttered-easy and cluttered-hard scenes, respectively. Real-world open-loop experiments on a Unitree Go2 further provide initial evidence of sim-to-real transfer and adaptation with L3ROcc-generated supervision.

## TL;DR

Pixel-goal navigation specifies targets directly in the agent's camera view, but a target pixel provides neither metric depth nor traversability, making 3D goal grounding and collision-free continuous planning challenging. We present OccPlanner, a goal-aware occupancy-conditioned diffusion planner that grounds pixel goals in egocentric metric space and sequentially conditions the goal representation on temporal visual context and learned local 3D occupancy features.

## Related
<!-- [[other-paper-citekey]] -->
