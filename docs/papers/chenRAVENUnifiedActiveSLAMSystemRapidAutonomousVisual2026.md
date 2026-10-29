---
citekey: "chenRAVENUnifiedActiveSLAMSystemRapidAutonomousVisual2026"
title: "RAVEN: A Unified Active SLAM System for Rapid Autonomous Visual Exploration with Aerial Robots under Localization Uncertainty"
authors: ["Xinyi Chen", "Yichen Zhang", "Chenxing Jiang", "Shaojie Shen"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.37111"
doi: "10.48550/arXiv.2610.37111"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-29
---

# RAVEN: A Unified Active SLAM System for Rapid Autonomous Visual Exploration with Aerial Robots under Localization Uncertainty

> Xinyi Chen, Yichen Zhang, Chenxing Jiang, Shaojie Shen · 2026
> [arXiv](https://arxiv.org/abs/2610.37111) · [PDF](https://arxiv.org/pdf/2610.37111)

## Abstract

Active simultaneous localization and mapping (SLAM) addresses the problem of planning robot motion to build complete and accurate maps of unknown environments through efficient exploration while maintaining high localization accuracy. This raises a dilemma between exploring unknown spaces to expand coverage and exploiting visited regions to perform active loop closures. Despite numerous prior works on ground robots, aerial robots with high agility and constrained sensor suites face more significant localization drift and thereby demand dedicated active SLAM planning. Moreover, a unified strategy that adapts performance based on task-specific priorities remains an open question. In this article, we introduce RAVEN, a unified active SLAM framework for Rapid Autonomous Visual ExploratioN using quadrotors, which systematically accounts for localization uncertainty. The framework starts with identifying frontiers and active loop closure candidates, from which global tour candidates are generated. These candidates are evaluated using a utility vector that separately quantifies exploration efficiency and localization accuracy, and the final tour is selected according to a prioritization parameter ranging from $[0,1]$. Finally, a perception-aware navigation planner generates smooth execution trajectories that minimize visual state estimation error based on the online Fisher information field that provides visual localization information in real-time. Benchmark evaluations demonstrate that RAVEN outperforms state-of-the-art active SLAM methods, highlighting its advantages in producing a spectrum of performance across prioritizations. Fully onboard field experiments with a customized stereo-inertial quadrotor further validate its practical applicability in challenging environments. The source code will be released to benefit the community.

## TL;DR

Active simultaneous localization and mapping (SLAM) addresses the problem of planning robot motion to build complete and accurate maps of unknown environments through efficient exploration while maintaining high localization accuracy. This raises a dilemma between exploring unknown spaces to expand coverage and exploiting visited regions to perform active loop closures.

## Related
<!-- [[other-paper-citekey]] -->
