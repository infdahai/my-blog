---
citekey: "liuUMIBridgeActionAnchoredLatentAlignmentHumanManipulation2026"
title: "UMI-Bridge: Action-Anchored Latent Alignment across Human and Robot Manipulation Data"
authors: ["Haiyi Liu", "Jingming Ma", "Ke Rui", "Yuteng Wei", "Yuan Ma", "Yushen Zuo", "Honglong Tian", "Haoran Jia", "Weitao Zhou", "Jiawei Wang", "Minglei Li", "Shiyi Chen", "Haiyan Mao", "Jiaqi Zhang", "Chun Zhang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.18232"
doi: "10.48550/arXiv.2609.18232"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-17
---

# UMI-Bridge: Action-Anchored Latent Alignment across Human and Robot Manipulation Data

> Haiyi Liu, Jingming Ma, Ke Rui, Yuteng Wei, Yuan Ma, Yushen Zuo, Honglong Tian, Haoran Jia, Weitao Zhou, Jiawei Wang, Minglei Li, Shiyi Chen, Haiyan Mao, Jiaqi Zhang, Chun Zhang · 2026
> [arXiv](https://arxiv.org/abs/2609.18232) · [PDF](https://arxiv.org/pdf/2609.18232)

## Abstract

Real-robot demonstrations are limited, motivating the use of human manipulation data collected without robots, including egocentric videos and handheld Universal Manipulation Interface (UMI) demonstrations. However, differences in viewpoint, embodiment, and available action supervision make it difficult to align representations across these sources according to manipulation motion rather than visual appearance. We introduce UMI-Bridge, which uses UMI as an intermediate domain to align representations according to action equivalence rather than pixel similarity. UMI action supervision anchors the latent representation to end-effector motion and gripper behavior, while synchronized head-wrist observations and paired ego-UMI clips support alignment across views and domains. We train a dual-view latent action model (LAM) on human manipulation data without robot demonstrations, then freeze its wrist teacher and dynamics model to regularize vision-language-action (VLA) post-training on UMI and robot data. The shared wrist interface enables this training-time supervision across both domains while preserving the policy's standard inference architecture. Across three real-robot tasks, UMI-Bridge achieves 91.7% mean success versus 73.3% for Naive Co-training with matched UMI and robot data. On two data-efficiency tasks, it surpasses a full-data Robot-only baseline using 25% of the robot demonstrations together with UMI data. It also achieves 85% and 90% success on two additional tasks learned from UMI demonstrations without task-specific robot demonstrations. These results support action-anchored latent alignment for data-efficient robot learning and UMI-to-robot task transfer.

## TL;DR

Real-robot demonstrations are limited, motivating the use of human manipulation data collected without robots, including egocentric videos and handheld Universal Manipulation Interface (UMI) demonstrations. However, differences in viewpoint, embodiment, and available action supervision make it difficult to align representations across these sources according to manipulation motion rather than visual appearance.

## Related
<!-- [[other-paper-citekey]] -->
