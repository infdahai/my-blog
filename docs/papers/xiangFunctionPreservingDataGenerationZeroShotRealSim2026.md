---
citekey: "xiangFunctionPreservingDataGenerationZeroShotRealSim2026"
title: "Function-Preserving Data Generation for Zero-Shot Real-to-Sim-to-Real Manipulation"
authors: ["Tianyi Xiang", "Xupeng Xie", "Jiahang Cao", "Andrew F. Luo", "Haoang Li", "Jun Ma"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.18293"
doi: "10.48550/arXiv.2609.18293"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-17
---

# Function-Preserving Data Generation for Zero-Shot Real-to-Sim-to-Real Manipulation

> Tianyi Xiang, Xupeng Xie, Jiahang Cao, Andrew F. Luo, Haoang Li, Jun Ma · 2026
> [arXiv](https://arxiv.org/abs/2609.18293) · [PDF](https://arxiv.org/pdf/2609.18293)

## Abstract

Robotic data generation is a promising paradigm for scaling robot learning without collecting large-scale real-world data. However, generating geometrically diverse yet physically valid data for contact-rich tasks remains challenging, especially when success depends on precise geometric interfaces. Standard shape augmentation methods often distort task-critical interfaces, resulting in invalid contact relationships, e.g., fit mismatches or interpenetration, rendering downstream interactions infeasible. To address these limitations, we propose a function-preserving Real-to-Sim-to-Real framework that generates synthetic demonstrations from reconstructed assets without teleoperated source trajectories. Our method augments task-relevant object geometries through constraint-guided mesh deformation, together with physically consistent transfer of task poses and collision proxies. Visual domain randomization is further applied during simulation rollouts, enabling robust zero-shot policy deployment without real-world fine-tuning. Extensive experiments in both real-world and simulation settings demonstrate that our method enables robust generalization across unseen object geometries and diverse visual conditions in contact-rich and long-horizon tasks. Our method provides a practical path toward scalable robot learning for contact-rich tasks via shape deformation.

## TL;DR

Robotic data generation is a promising paradigm for scaling robot learning without collecting large-scale real-world data. However, generating geometrically diverse yet physically valid data for contact-rich tasks remains challenging, especially when success depends on precise geometric interfaces.

## Related
<!-- [[other-paper-citekey]] -->
