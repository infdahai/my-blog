---
citekey: "zhangCrossEmbodimentCausalTransferHumanVideosManipulation2026"
title: "Cross-Embodiment Causal Transfer from Human Videos to Robot Manipulation"
authors: ["Xingyu Zhang", "Yingchao Li", "Peizheng Guo", "Jie Hu", "Changwen Zheng", "Wenwen Qiang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.21798"
doi: "10.48550/arXiv.2610.21798"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-10-18
---

# Cross-Embodiment Causal Transfer from Human Videos to Robot Manipulation

> Xingyu Zhang, Yingchao Li, Peizheng Guo, Jie Hu, Changwen Zheng, Wenwen Qiang · 2026
> [arXiv](https://arxiv.org/abs/2610.21798) · [PDF](https://arxiv.org/pdf/2610.21798)

## Abstract

Scaling robot manipulation models requires large amounts of interaction data, yet collecting diverse real-robot experience remains costly. Human manipulation videos, in contrast, provide abundant and diverse task experience that could potentially benefit robot learning. However, differences in morphology, action spaces, and control mechanisms make human motions unsuitable as direct supervision for robot actions, raising a scientific question: what knowledge in human videos should be transferred across embodiments to robot manipulation? To address this question, we analyze subtask transfer through the lens of causal beams, focusing on which contextual conditions and interaction dependencies should be retained to support local task effects. Based on this perspective, we propose Causal-Beam-Guided Subtask Transfer (CBST). CBST learns manipulation-related representations from human videos and grounds them in task-level semantic variables using robot demonstrations. Within a predefined manipulation model, causal-beam constraints guide contextual information selection by requiring retained assignments to sustain local mechanism outputs while preserving nontrivial responsiveness to retained inputs. The selected semantic information conditions a world-action model, allowing the robot to generate actions from its own observations without requiring human-robot motion correspondence. Experiments on robot manipulation benchmarks show improvements in task success over the corresponding world-action model baselines.

## TL;DR

Scaling robot manipulation models requires large amounts of interaction data, yet collecting diverse real-robot experience remains costly. Human manipulation videos, in contrast, provide abundant and diverse task experience that could potentially benefit robot learning.

## Related
<!-- [[other-paper-citekey]] -->
