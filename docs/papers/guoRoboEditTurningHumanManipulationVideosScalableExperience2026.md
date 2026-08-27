---
citekey: "guoRoboEditTurningHumanManipulationVideosScalableExperience2026"
title: "RoboEdit: Turning Human Manipulation Videos into Scalable Robot Experience"
authors: ["Yaowei Guo", "Zeng Tao", "Yuxin Jiang", "Yunuo Chen", "Zhiyang Dou", "Yuxiang Ma", "Yin Yang", "Demetri Terzopoulos", "Ying Jiang", "Chenfanfu Jiang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.18948"
doi: "10.48550/arXiv.2608.18948"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# RoboEdit: Turning Human Manipulation Videos into Scalable Robot Experience

> Yaowei Guo, Zeng Tao, Yuxin Jiang, Yunuo Chen, Zhiyang Dou, Yuxiang Ma, Yin Yang, Demetri Terzopoulos, Ying Jiang, Chenfanfu Jiang · 2026
> [arXiv](https://arxiv.org/abs/2608.18948) · [PDF](https://arxiv.org/pdf/2608.18948)

## Abstract

Collecting robot hand-object interaction data is costly and embodiment-specific, yet abundant human-object videos remain unusable for robot training. We present RoboEdit, a human-to-robot video editing suite that transforms human manipulation videos into action-consistent, physically plausible robot videos with aligned 3D hand states. To enable scalable supervision, we introduce RoboEdit-ADC, an automatic pipeline that reconstructs and retargets 3D interactions from RGB videos across embodiments. This pipeline generates RoboEdit-14M, a large-scale dataset of 174K aligned video pairs (14M frames) spanning seven robot embodiments, diverse scenes, and interaction types. The core editing engine, RoboEdit-Trans, employs cross-embodiment adaptation modules to preserve temporal coherence while adapting appearance and motion. It further integrates a 3D Robot-State Decoder to recover per-frame hand states for structured motion supervision. Experiments show that RoboEdit achieves state-of-the-art editing quality and supports downstream robot control policies in real-world manipulation tasks. Ultimately, the RoboEdit suite unlocks the vast potential of unlabeled human videos, providing scalable, high-fidelity visual and 3D motion supervision for generalizable robot learning.

## TL;DR

Collecting robot hand-object interaction data is costly and embodiment-specific, yet abundant human-object videos remain unusable for robot training. We present RoboEdit, a human-to-robot video editing suite that transforms human manipulation videos into action-consistent, physically plausible robot videos with aligned 3D hand states.

## Related
<!-- [[other-paper-citekey]] -->
