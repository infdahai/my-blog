---
citekey: "luoTouch2RobotTouchHumanDemonstrationLoop2026"
title: "Touch2Robot: Robot Touch in the Human Demonstration Loop"
authors: ["Shengcheng Luo", "Xiaoyang Cheng", "Hong Ying", "Xiaoying Zhou", "Jiaming Jiang", "Haoran Guo", "Wanlin Li", "Ziyuan Jiao", "Chenxi Xiao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.24660"
doi: "10.48550/arXiv.2609.24660"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-09-23
---

# Touch2Robot: Robot Touch in the Human Demonstration Loop

> Shengcheng Luo, Xiaoyang Cheng, Hong Ying, Xiaoying Zhou, Jiaming Jiang, Haoran Guo, Wanlin Li, Ziyuan Jiao, Chenxi Xiao · 2026
> [arXiv](https://arxiv.org/abs/2609.24660) · [PDF](https://arxiv.org/pdf/2609.24660)

## Abstract

Human demonstrations offer a scalable way to collect manipulation data, but their contacts may be unstable or infeasible when transferred to a robot hand. Collecting demonstrations directly on the target robot avoids this mismatch but substantially increases the cost of data collection. To address this trade-off, we present Touch2Robot, a framework that lets humans collect demonstrations while seeing how the target robot hand would contact the object. We capture human hand motion, tactile-glove measurements, and object motion during human manipulation. These recordings guide object-specific RL policies to reproduce the demonstrated object motion while favoring contacts consistent with the recorded human touch. We distill the learned behaviors into a unified real-time retargeter that maps incoming human observations and object geometry to robot hand configurations. During collection, the predicted robot configuration is synchronized with the tracked object pose in simulation to reconstruct robot-object contacts, which are visualized to help the demonstrator adapt subsequent interactions to the target hand. Across four real-world tasks, Touch2Robot improves average real-robot replay completion from 37.9% to 72.1% over visual-only feedback, while reducing the collection time per replay-successful demonstration from 58.6s to 18.2s. Reconstructed target-hand contacts achieve 44.2% F1 against real-robot tactile measurements, and policies trained on Touch2Robot demonstrations improve downstream Diffusion Policy performance by 29.1 percentage points over visual-only feedback. These results show that bringing robot touch into the human demonstration loop improves both the quality and efficiency of scalable dexterous data collection. Project webpage: https://Touch2Robot.github.io/.

## TL;DR

Human demonstrations offer a scalable way to collect manipulation data, but their contacts may be unstable or infeasible when transferred to a robot hand. Collecting demonstrations directly on the target robot avoids this mismatch but substantially increases the cost of data collection.

## Related
<!-- [[other-paper-citekey]] -->
