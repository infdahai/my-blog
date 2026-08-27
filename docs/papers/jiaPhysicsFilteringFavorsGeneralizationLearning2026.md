---
citekey: "jiaPhysicsFilteringFavorsGeneralizationLearning2026"
title: "Physics Filtering Favors the Generalization of Robot Learning"
authors: ["Jindou Jia", "Shixuan Han", "Meng Wang", "Gen Li", "Zihan Yang", "Sicheng Zhou", "Kexin Guo", "Jianfei Yang", "Xiang Yu", "Wei Wang", "Lei Guo"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.22701"
doi: "10.48550/arXiv.2608.22701"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# Physics Filtering Favors the Generalization of Robot Learning

> Jindou Jia, Shixuan Han, Meng Wang, Gen Li, Zihan Yang, Sicheng Zhou, Kexin Guo, Jianfei Yang, Xiang Yu, Wei Wang, Lei Guo · 2026
> [arXiv](https://arxiv.org/abs/2608.22701) · [PDF](https://arxiv.org/pdf/2608.22701)

## Abstract

Living organisms exhibit extraordinary adaptability to unseen environments through their intrinsic physical structures and lifelong feedback-driven learning. Endowing robots with comparable generalization is critical for reliable operation in the real world. While recent approaches attempt to improve generalization by scaling training data, such strategies remain impractical for robotics, where collecting real-world demonstrations at the scale of large language models is prohibitively costly and slow. Contrary to this reliance on massive datasets, we show that robots can generalize effectively under dynamics uncertainties even with limited training data by leveraging a feedback mechanism, namely PhyFilter, that corrects learning outputs with physics-filtered learning residuals. PhyFilter operates as a lightweight, model-agnostic module whose parameters can be automatically optimized through an auto-learning algorithm, eliminating manual tuning and enabling seamless integration with diverse robot policies. We validate PhyFilter across four representative robotic systems, demonstrating that it enables quadruped robots to generalize to unseen terrains, payload variations, and speed ranges; drones to flight under unseen wind disturbances; aerial manipulators to achieve centimeter-level in-air capture despite wind and mass uncertainties; and acceleration differentiators to remain robust with distribution shift. These results show that physics-filtered feedback can serve as a powerful alternative to massive data scaling.

## TL;DR

Living organisms exhibit extraordinary adaptability to unseen environments through their intrinsic physical structures and lifelong feedback-driven learning. Endowing robots with comparable generalization is critical for reliable operation in the real world.

## Related
<!-- [[other-paper-citekey]] -->
