---
citekey: "luoReFHILShapingCriticAroundHumanActionNeighborhoods2026"
title: "ReF-HIL: Shaping the Critic around Human Action Neighborhoods for Efficient Human-in-the-Loop Reinforcement Learning"
authors: ["Shaoyin Luo", "Song Wang", "Shibo Xia", "Tianle Zhang", "Zhaowei Liang", "Guanghui Shen", "Bin Wang", "Dan Wu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.37131"
doi: "10.48550/arXiv.2609.37131"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# ReF-HIL: Shaping the Critic around Human Action Neighborhoods for Efficient Human-in-the-Loop Reinforcement Learning

> Shaoyin Luo, Song Wang, Shibo Xia, Tianle Zhang, Zhaowei Liang, Guanghui Shen, Bin Wang, Dan Wu · 2026
> [arXiv](https://arxiv.org/abs/2609.37131) · [PDF](https://arxiv.org/pdf/2609.37131)

## Abstract

Human-in-the-loop reinforcement learning (HIL-RL) offers a promising route to efficient training of robotic manipulation policies by combining autonomous learning with human demonstrations and online corrections. However, insufficient use of successful human experience in value learning prolongs costly real-world training, while persistent imitation penalties can limit value-driven policy improvement. To address these limitations, we propose ReF-HIL, an efficient HIL-RL framework that uses human guidance to accelerate the learning process. Human-Reference-Guided Value Shaping learns an independent value reference from successful human experience to guide online value learning, while incorporating local corrective feedback. A Human Action Fence defines a learned human-action neighborhood, allowing value-driven optimization for better performance without imitation penalties inside while constraining policy and value updates outside. Experiments on five diverse and challenging real-world manipulation tasks demonstrate improved overall learning efficiency and higher success rates compared with the evaluated baselines. Specifically, ReF-HIL reaches 90% autonomous success in only 18-63 minutes of active training and achieves final success rates of 91.7-100%. These results highlight the potential of human-guided reinforcement learning to acquire reliable manipulation skills efficiently in the real world. Project website: https://anonymous.4open.science/w/ReF-HIL-7762/

## TL;DR

Human-in-the-loop reinforcement learning (HIL-RL) offers a promising route to efficient training of robotic manipulation policies by combining autonomous learning with human demonstrations and online corrections. However, insufficient use of successful human experience in value learning prolongs costly real-world training, while persistent imitation penalties can limit value-driven policy improvement.

## Related
<!-- [[other-paper-citekey]] -->
