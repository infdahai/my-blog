---
citekey: "langEmbodiRSIRecursiveSelfImprovementDataEfficientAdaptation2026"
title: "EmbodiRSI: Recursive Self-Improvement for Data-Efficient Robot Adaptation"
authors: ["Haoran Lang", "Haotao Lu", "Shiyu Sang", "Haoyang Luo", "Guo Chen", "Qun Li", "Jingyi Yu", "Ye Shi", "Jingya Wang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.38905"
doi: "10.48550/arXiv.2609.38905"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# EmbodiRSI: Recursive Self-Improvement for Data-Efficient Robot Adaptation

> Haoran Lang, Haotao Lu, Shiyu Sang, Haoyang Luo, Guo Chen, Qun Li, Jingyi Yu, Ye Shi, Jingya Wang · 2026
> [arXiv](https://arxiv.org/abs/2609.38905) · [PDF](https://arxiv.org/pdf/2609.38905)

## Abstract

Adapting robot manipulation policies to new tasks and environments remains highly data-intensive, while the data needed for further improvement depends on the policy's current capabilities and failure modes. We introduce EmbodiRSI, an agentic system for recursive self-improvement (RSI) in a real-to-sim-to-real setting, where task-specific simulations are constructed from target deployment scenarios and used as low-cost environments for iterative policy improvement before transfer back to the physical world. EmbodiRSI uses policy execution feedback to guide subsequent experience acquisition and policy updates. Two complementary mechanisms close this loop: Collaborative Error Correction generates agent-assisted corrective trajectories from policy-reached states, while Adaptive Data Collection directs expert demonstration generation toward the current policy's weaknesses. The task-specific simulation serves as a reusable workspace for policy warm-up, repeatable evaluation, failure diagnosis, and targeted data generation across successive RSI rounds. Across three tabletop environments and 14 subtasks, EmbodiRSI increases scene-balanced autonomous simulation success from 50.4% to 83.5% over two RSI updates. With 400 adaptive simulated trajectories and only ten real-world refinement trajectories per subtask, EmbodiRSI achieves 83.1% scene-balanced autonomous real-world success, compared with 75.0% for adaptation using 200 real-world demonstrations per subtask. These results demonstrate that feedback-driven recursive improvement in deployment-specific simulations can enable data-efficient adaptation of embodied policies to physical environments.

## TL;DR

Adapting robot manipulation policies to new tasks and environments remains highly data-intensive, while the data needed for further improvement depends on the policy's current capabilities and failure modes. We introduce EmbodiRSI, an agentic system for recursive self-improvement (RSI) in a real-to-sim-to-real setting, where task-specific simulations are constructed from target deployment scenarios and used as low-cost environments for iterative policy improvement before transfer back to the physical world.

## Related
<!-- [[other-paper-citekey]] -->
