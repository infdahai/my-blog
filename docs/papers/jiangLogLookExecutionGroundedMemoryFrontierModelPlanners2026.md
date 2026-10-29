---
citekey: "jiangLogLookExecutionGroundedMemoryFrontierModelPlanners2026"
title: "LogLook: Execution-Grounded Memory for Frontier-Model Robot Planners"
authors: ["Tianyi Jiang", "Tianyao Tong", "Zhenshan Bing"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.32348"
doi: "10.48550/arXiv.2610.32348"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-27
---

# LogLook: Execution-Grounded Memory for Frontier-Model Robot Planners

> Tianyi Jiang, Tianyao Tong, Zhenshan Bing · 2026
> [arXiv](https://arxiv.org/abs/2610.32348) · [PDF](https://arxiv.org/pdf/2610.32348)

## Abstract

Many manipulation tasks require a robot to remember what it has done and what it has seen. Frontier vision-language models can plan such tasks without task-specific training, but how such a planner should remember an episode is an open question. We argue that its memory must keep track of what the planner has done and learned, and must let the planner choose what to look at, since every frame costs tokens; a note rewritten at every step meets both poorly. We propose LogLook, whose execution-grounded memory lets the system keep the record, an execution log and the model's earlier notes, while the model decides where to look: frames are returned only where it expects a change, and demonstrations are skimmed before it inspects the parts it chooses. Measured with the benchmark's motion planner, LogLook matches the success of a note-only memory with 43% fewer tokens and less than half the images, and fails far fewer episodes through what it remembered or saw. With direct control, LogLook solves 93.5% of the RoboMME test set.

## TL;DR

Many manipulation tasks require a robot to remember what it has done and what it has seen. Frontier vision-language models can plan such tasks without task-specific training, but how such a planner should remember an episode is an open question.

## Related
<!-- [[other-paper-citekey]] -->
