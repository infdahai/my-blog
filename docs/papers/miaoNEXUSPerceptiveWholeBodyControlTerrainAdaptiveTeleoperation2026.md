---
citekey: "miaoNEXUSPerceptiveWholeBodyControlTerrainAdaptiveTeleoperation2026"
title: "NEXUS: Perceptive Whole-Body Control for Terrain-Adaptive Teleoperation"
authors: ["Xiangyu Miao", "Junsong Wu", "Jiyuan Shi", "Weiji Xie", "Jinrui Han", "Xingyi Wang", "Weinan Zhang", "Chenjia Bai", "Xuelong Li"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.39000"
doi: "10.48550/arXiv.2609.39000"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-04
---

# NEXUS: Perceptive Whole-Body Control for Terrain-Adaptive Teleoperation

> Xiangyu Miao, Junsong Wu, Jiyuan Shi, Weiji Xie, Jinrui Han, Xingyi Wang, Weinan Zhang, Chenjia Bai, Xuelong Li · 2026
> [arXiv](https://arxiv.org/abs/2609.39000) · [PDF](https://arxiv.org/pdf/2609.39000)

## Abstract

Whole-body teleoperation requires a humanoid robot to reproduce a human operator's behavior even when their terrains differ. This demands that the robot perceive local terrain and adapt its posture and contacts accordingly, rather than copy the operator's motion frame by frame. However, paired motion data linking the same behaviors across flat ground and different terrains remain scarce, limiting supervision for learning terrain-adaptive control. To enable whole-body teleoperation across mismatched terrains, we introduce NEXUS, a perceptive whole-body control framework that combines human motion commands with onboard sensory feedback. We first develop a scalable terrain-aware adaptation algorithm that efficiently generates high-quality motion pairs across motions and terrains without per-motion or per-terrain tuning. Using a paired motion corpus totaling nearly 1,000 hours, we train a perceptive whole-body controller through teacher-student learning to reproduce commanded behaviors across terrains. Experiments demonstrate efficient, scalable generation of high-quality motion data and show that NEXUS combines broad behavioral coverage with terrain adaptability and tracking fidelity, outperforming existing whole-body controllers on the evaluated benchmarks. Zero-shot real-world deployment enables real-time whole-body teleoperation on diverse unseen terrains, further validating the generalization of our method. Project website: https://nexus-humanoid.github.io/

## TL;DR

Whole-body teleoperation requires a humanoid robot to reproduce a human operator's behavior even when their terrains differ. This demands that the robot perceive local terrain and adapt its posture and contacts accordingly, rather than copy the operator's motion frame by frame.

## Related
<!-- [[other-paper-citekey]] -->
