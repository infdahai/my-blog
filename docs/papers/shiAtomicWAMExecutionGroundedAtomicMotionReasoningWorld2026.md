---
citekey: "shiAtomicWAMExecutionGroundedAtomicMotionReasoningWorld2026"
title: "Atomic-WAM: Execution-Grounded Atomic-Motion Reasoning for World Action Models"
authors: ["Shijun Shi", "Zhe Liu", "Zhi Hou", "Yinan Chen", "Tao Zhang", "Kai Hu", "Yong Liu", "Jiangning Zhang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.20157"
doi: "10.48550/arXiv.2610.20157"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-16
---

# Atomic-WAM: Execution-Grounded Atomic-Motion Reasoning for World Action Models

> Shijun Shi, Zhe Liu, Zhi Hou, Yinan Chen, Tao Zhang, Kai Hu, Yong Liu, Jiangning Zhang · 2026
> [arXiv](https://arxiv.org/abs/2610.20157) · [PDF](https://arxiv.org/pdf/2610.20157)

## Abstract

World Action Models (WAMs) typically adapt video foundation models to robotic control through joint video and action prediction. However, task-level instructions may leave the next physical interaction underspecified, requiring semantic grounding and state-dependent motion selection. To this end, we introduce Atomic-WAM, an understand-then-execute framework that connects task reasoning to action generation through atomic-motion descriptions. Specifically, a vision-language reasoner describes the next local motion from the task instruction and visual context, guiding a WAM to predict future video and an action chunk. Furthermore, an automatic annotation pipeline curates temporally aligned, contact-enriched supervision from multi-view DROID demonstrations. To make atomic-motion predictions executable by the WAM, we post-train the reasoner with Execution-Grounded GRPO (EG-GRPO). With the WAM fixed, EG-GRPO adapts the reasoner through rewards for motion appropriateness and execution success. Finally, Atomic-WAM achieves 39.6% task success under default instructions and 31.6% under vague instructions in a real-to-sim evaluation on RoboLab. Project page: https://ssj9596.github.io/Atomic-WAM-project

## TL;DR

World Action Models (WAMs) typically adapt video foundation models to robotic control through joint video and action prediction. However, task-level instructions may leave the next physical interaction underspecified, requiring semantic grounding and state-dependent motion selection.

## Related
<!-- [[other-paper-citekey]] -->
