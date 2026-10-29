---
citekey: "linTONAVTaskOrientedNavigationActionVelocityChunkLearning2026"
title: "TONAV: Task-Oriented Navigation and Action-Velocity Chunk Learning for Articulated Object Quadrupedal Mobile Manipulation"
authors: ["Haoran Lin", "Mingyu Yang", "Pengfei Qi", "Kehan Chen", "Qiang Diao", "Liangji Zeng", "Wenrui Chen", "Yaonan Wang", "Kailun Yang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.22296"
doi: "10.48550/arXiv.2608.22296"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-08
---

# TONAV: Task-Oriented Navigation and Action-Velocity Chunk Learning for Articulated Object Quadrupedal Mobile Manipulation

> Haoran Lin, Mingyu Yang, Pengfei Qi, Kehan Chen, Qiang Diao, Liangji Zeng, Wenrui Chen, Yaonan Wang, Kailun Yang · 2026
> [arXiv](https://arxiv.org/abs/2608.22296) · [PDF](https://arxiv.org/pdf/2608.22296)

## Abstract

Quadruped mobile manipulation requires two tightly coupled capabilities: reaching manipulation-ready configurations and maintaining stable contact throughout articulated-object interaction. However, existing methods often terminate navigation near the target, leaving a gap between reachability and manipulation readiness, while tracking lag, motion jitter, and contact instability limit continuous interaction. To address these challenges, we present TONAV, a unified framework integrating task-oriented navigation with action-velocity chunk learning. First, we introduce a position-velocity-coupled teleoperation framework that explicitly captures motion dynamics to improve master-follower consistency and collect smooth, temporally consistent demonstrations. Next, task-oriented navigation leverages vision-language reasoning to decompose high-level instructions into executable subgoals and adaptively refine the robot base toward a manipulation-ready configuration. Finally, action-velocity chunk learning jointly models joint positions and their temporal transitions under velocity supervision, enabling smooth and stable sustained-contact manipulation. Real-world experiments across diverse articulated-object tasks demonstrate that TONAV achieves higher success rates in both task-oriented navigation and complete mobile manipulation, mitigating the navigation-manipulation gap and improving continuous-contact interaction. The project page is at https://haochen611.github.io/TONAV.

## TL;DR

Quadruped mobile manipulation requires two tightly coupled capabilities: reaching manipulation-ready configurations and maintaining stable contact throughout articulated-object interaction. However, existing methods often terminate navigation near the target, leaving a gap between reachability and manipulation readiness, while tracking lag, motion jitter, and contact instability limit continuous interaction.

## Related
<!-- [[other-paper-citekey]] -->
