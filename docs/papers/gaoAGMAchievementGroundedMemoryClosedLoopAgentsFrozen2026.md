---
citekey: "gaoAGMAchievementGroundedMemoryClosedLoopAgentsFrozen2026"
title: "AGM: Achievement-Grounded Memory for Closed-Loop Agents with Frozen VLA Policies"
authors: ["Hongbo Gao", "Zeyu Ni", "Xin Wen", "Siyu Xu", "Ruifeng Li"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.29537"
doi: "10.48550/arXiv.2608.29537"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-09-02
---

# AGM: Achievement-Grounded Memory for Closed-Loop Agents with Frozen VLA Policies

> Hongbo Gao, Zeyu Ni, Xin Wen, Siyu Xu, Ruifeng Li · 2026
> [arXiv](https://arxiv.org/abs/2608.29537) · [PDF](https://arxiv.org/pdf/2608.29537)

## Abstract

Frozen vision-language-action (VLA) policies offer broad manipulation skills but execute open-loop action chunks without tracking task progress, so the agent cannot reliably decide whether to continue, retry, or terminate. External memory is a natural remedy, yet it can be harmful when attempted actions are treated as completed progress, turning local execution errors into persistent task-state errors. We propose Achievement-Grounded Memory (AGM), a lightweight closed-loop framework for frozen VLA policies that represents a task as a subgoal sequence with a progress pointer and advances this memory only after the current subgoal is verified by physical evidence. Proprioceptive interaction cues decide when to verify, while coherent point tracking and language-conditioned cross-view comparison, sourced from frozen foundation models through a single 2.43M-parameter verification head, decide what was achieved. AGM thereby converts open-loop execution into a closed loop of execution, verification, and progress, keeping the policy frozen without test-time large-model inference. On the RoboMME Counting benchmark, AGM reaches on PickXTimes and on BinFill, surpassing the strongest memory-augmented baseline by points on average, and the framework yields equally decisive gains on a physical robot. Reliable embodied memory thus depends more on disciplined state updates than on memory capacity.

## TL;DR

Frozen vision-language-action (VLA) policies offer broad manipulation skills but execute open-loop action chunks without tracking task progress, so the agent cannot reliably decide whether to continue, retry, or terminate. External memory is a natural remedy, yet it can be harmful when attempted actions are treated as completed progress, turning local execution errors into persistent task-state errors.

## Related
<!-- [[other-paper-citekey]] -->
