---
citekey: "shirasakaRoboPaceContactAwareTimeOptimalRetimingActionChunk2026"
title: "RoboPace: Contact-Aware Time-Optimal Retiming for Action-Chunk Policies"
authors: ["Mimo Shirasaka", "Takehiko Ohkawa", "Takuya Okubo", "Nicola Scianca", "Tatsuya Matsushima", "Kei Ota"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.09696"
doi: "10.48550/arXiv.2610.09696"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-09
---

# RoboPace: Contact-Aware Time-Optimal Retiming for Action-Chunk Policies

> Mimo Shirasaka, Takehiko Ohkawa, Takuya Okubo, Nicola Scianca, Tatsuya Matsushima, Kei Ota · 2026
> [arXiv](https://arxiv.org/abs/2610.09696) · [PDF](https://arxiv.org/pdf/2610.09696)

## Abstract

Robot manipulation data collection has been shifting from teleoperation toward robot-free demonstrations, through interfaces such as the Universal Manipulation Interface (UMI) or directly from human hands. Vision-Language-Action (VLA) policies trained on such data inherit the demonstrator's timing. Yet human timing does not directly transfer to robots: compliant hands tolerate fast contact, whereas robots may overshoot due to actuator and tracking limitations; conversely, robots can move faster in free space. This motivates a unified approach that reconciles execution speed with contact safety. We present RoboPace, an online retiming layer that preserves the policy's geometric path while adapting its timing, respecting the target robot's kinematic and dynamic constraints. It adapts execution speed based on predicted contact, jointly accounting for contact-dependent speed limits and the robot's motion constraints. The method requires no policy retraining and operates in real time. Across three contact-rich tasks on a dual-arm robot, faster uniform execution and physical-limit-only retiming largely fail. RoboPace instead achieves higher overall success than slow uniform execution while completing four of five commands in approximately half the time, retaining the reliability of slow execution without its time cost.

## TL;DR

Robot manipulation data collection has been shifting from teleoperation toward robot-free demonstrations, through interfaces such as the Universal Manipulation Interface (UMI) or directly from human hands. Vision-Language-Action (VLA) policies trained on such data inherit the demonstrator's timing.

## Related
<!-- [[other-paper-citekey]] -->
