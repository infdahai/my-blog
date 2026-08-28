---
citekey: "rathiRoboMMEInterferenceBenchmarkingMemoryInterference2026"
title: "RoboMME-Interference: Benchmarking Robot Memory Under Interference"
authors: ["Soumil Rathi"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2606.22338"
doi: "10.48550/arXiv.2606.22338"
tags: [paper, embodied-ai, "cs.AI", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-08-28
---

# RoboMME-Interference: Benchmarking Robot Memory Under Interference

> Soumil Rathi · 2026
> [arXiv](https://arxiv.org/abs/2606.22338) · [PDF](https://arxiv.org/pdf/2606.22338)

## Abstract

Robots deployed in realistic settings will accumulate experience across many sessions and tasks over their deployment. The robot's tasks may often require it to remember information from multiple sessions ago, making long-context robot memory important for real-world deployments. However, most robot-memory benchmarks today are based on single episodes or a short context. To measure how current robot memory systems perform on longer sessions with more distractions, we introduce RoboMME-Interference, a cross-session benchmark built on RoboMME (Dai et al., 2026). For each query episode, we construct a session history using the query's relevant prior demonstration followed by a controlled number of unrelated sessions, which we provide to the VLA as memory and measure accuracy. Running RoboMME's released memory-augmented $\pi_{0.5}$ variants unmodified through this benchmark, we find that while perceptual memory variants improve success when given the history without any distractors, they decay strongly and steadily as unrelated sessions accumulate. The subgoal variants, which read the history with a vision-language model and pass written subgoals to the policy, improve less at their best but hold more of that improvement as distractors accumulate. Adding a retrieval step to the strongest perceptual variant, which selects the section of history most visually similar to the robot's current view and passes only that section to the policy, restores its no-distractor success rate at every interference level. With this release, we emphasize the importance of long-context memory and robustness to interference and show that current systems largely fail on such capabilities. The project page, videos, code, and data are at https://robotmemorybench.com.

## TL;DR

Robots deployed in realistic settings will accumulate experience across many sessions and tasks over their deployment. The robot's tasks may often require it to remember information from multiple sessions ago, making long-context robot memory important for real-world deployments.

## Related
<!-- [[other-paper-citekey]] -->
