---
citekey: "guoCAGWAMCausalActionGainWorldActionModels2026"
title: "CAG-WAM: Causal Action-Gain World Action Models for Robot Manipulation"
authors: ["Peizheng Guo", "Cheng Zhang", "Xingyu Zhang", "Changwen Zheng", "Wenwen Qiang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.14720"
doi: "10.48550/arXiv.2610.14720"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-15
---

# CAG-WAM: Causal Action-Gain World Action Models for Robot Manipulation

> Peizheng Guo, Cheng Zhang, Xingyu Zhang, Changwen Zheng, Wenwen Qiang · 2026
> [arXiv](https://arxiv.org/abs/2610.14720) · [PDF](https://arxiv.org/pdf/2610.14720)

## Abstract

World Action Models (WAMs) combine action generation with future prediction, allowing predicted futures to support action evaluation and robot decision making. However, the future associated with a candidate action may contain action-induced and environment-driven changes. Directly evaluating the predicted future may not fully characterize the future change associated with the candidate action. For example, a candidate action that worsens a favorable environmental future may still yield a favorable outcome, while one that improves an unfavorable environmental future may still yield an unfavorable outcome. To analyze this issue, we formulate a Structural Causal Model (SCM) for action evaluation in WAMs. The SCM formalizes how action-induced and environment-driven changes jointly shape future evaluation, and reveals a backdoor path through which environmental evolution can also affect the future evaluation associated with a candidate action. Intervention and backdoor adjustment account for this path, providing a causal basis for characterizing the future change associated with each candidate action. Based on this analysis, we propose Causal Action-Gain World Action Model (CAG-WAM). For each candidate action, CAG-WAM predicts an action-conditioned future and an environmental future under the same current observation, and defines their evaluation difference as causal action gain (CAG) for characterizing the future change associated with the candidate action. During training, we incorporate CAG into Group Relative Policy Optimization (GRPO) to guide robot policy learning. During inference, we evaluate the initial action with CAG and, when needed, revise it using predicted future information. Experiments on multiple benchmarks support the effectiveness of CAG-WAM.

## TL;DR

World Action Models (WAMs) combine action generation with future prediction, allowing predicted futures to support action evaluation and robot decision making. However, the future associated with a candidate action may contain action-induced and environment-driven changes.

## Related
<!-- [[other-paper-citekey]] -->
