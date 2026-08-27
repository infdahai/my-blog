---
citekey: "zhaoAXISGrowableCommunityDrivenDataEngineScalableManipulation2026"
title: "AXIS: A Growable Community-Driven Data Engine for Scalable Robot Manipulation"
authors: ["Mengfei Zhao", "Dihong Huang", "Yikai Tang", "Peihao Li", "Mingxuan Yan", "Ruiqi Zhuang", "Yanjia Huang", "Jie Wang", "Hai Zhai", "Tony Zhou", "Rui Zhang", "Zhexi Luo", "Yuchen Huang", "Jianfei Yang", "Jiachen Li"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2607.21588"
doi: "10.48550/arXiv.2607.21588"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# AXIS: A Growable Community-Driven Data Engine for Scalable Robot Manipulation

> Mengfei Zhao, Dihong Huang, Yikai Tang, Peihao Li, Mingxuan Yan, Ruiqi Zhuang, Yanjia Huang, Jie Wang, Hai Zhai, Tony Zhou, Rui Zhang, Zhexi Luo, Yuchen Huang, Jianfei Yang, Jiachen Li · 2026
> [arXiv](https://arxiv.org/abs/2607.21588) · [PDF](https://arxiv.org/pdf/2607.21588)

## Abstract

Learning effective robot manipulation policies requires diverse, high-quality demonstrations, yet existing data pipelines are often difficult to scale because they rely on specialized hardware, centralized operators, or fixed task suites. We present AXIS, a growable community-driven data engine and benchmark for scalable robot learning, which enables browser-based teleoperation for large-scale demonstration collection, automatically generates and validates new manipulation tasks, and transforms community-collected demonstrations into training-ready data through automated success checking, quality filtering, trajectory smoothing, and visual and physics-based augmentation. The AXIS dataset currently contains 207 diverse tasks and 50K+ trajectories. Meanwhile, AXIS organizes data into task snapshots and evaluates policies with a systematic held-out protocol. We compare vision-language-action (VLA) policies under a unified AXIS evaluation suite and analyze scaling behavior across different data volumes. Continual pretraining on AXIS substantially improves the overall success rate of $π_{0.5}$ by 5.8%, outperforms the model pretrained on RoboCasa365 by 37.3%, and exhibits consistent scaling with increasing data volume, with the largest gains observed under layout, sensor-noise, and camera perturbations.

## TL;DR

Learning effective robot manipulation policies requires diverse, high-quality demonstrations, yet existing data pipelines are often difficult to scale because they rely on specialized hardware, centralized operators, or fixed task suites. We present AXIS, a growable community-driven data engine and benchmark for scalable robot learning, which enables browser-based teleoperation for large-scale demonstration collection, automatically generates and validates new manipulation tasks, and transforms community-collected demonstrations into training-ready data through automated success checking,...

## Related
<!-- [[other-paper-citekey]] -->
