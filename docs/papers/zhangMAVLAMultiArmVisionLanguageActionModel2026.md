---
citekey: "zhangMAVLAMultiArmVisionLanguageActionModel2026"
title: "MA-VLA: Multi-Arm Vision-Language-Action Model for Collaboration and Compositional Generalization"
authors: ["Zaibin Zhang", "Junlan Xiao", "Zhongbo Zhang", "Yifan Wang", "Li Kang", "Yiran Qin", "Changxing Xia", "Heng Zhou", "Talas Fu", "Enshen Zhou", "Ruimao Zhang", "Zhenfei Yin", "Huchuan Lu", "Lijun Wang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.25864"
doi: "10.48550/arXiv.2608.25864"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# MA-VLA: Multi-Arm Vision-Language-Action Model for Collaboration and Compositional Generalization

> Zaibin Zhang, Junlan Xiao, Zhongbo Zhang, Yifan Wang, Li Kang, Yiran Qin, Changxing Xia, Heng Zhou, Talas Fu, Enshen Zhou, Ruimao Zhang, Zhenfei Yin, Huchuan Lu, Lijun Wang · 2026
> [arXiv](https://arxiv.org/abs/2608.25864) · [PDF](https://arxiv.org/pdf/2608.25864)

## Abstract

Multi-arm collaboration is becoming a core capability in embodied manipulation. Recent vision-language-action (VLA) models integrate perception, language, and control, but most represent language as a single global instruction and do not provide an explicit mechanism for assigning and composing arm-specific behaviors. This design limits transfer to collaboration patterns that differ from those observed during training. We present MA-VLA, a unified framework for multi-arm collaboration via atomic action assignment. MA-VLA decomposes cooperative behavior into mid-level atomic prompts and allocates them to individual arms, enabling explicit subgoal specification and compositional reuse across tasks. To reduce reliance on fixed execution roles, we introduce Arm Shuffle, a training-time permutation of the observation, state, and assigned atomic prompts for each arm. This permutation enforces role-agnostic instruction following and supports recomposition into unseen coordination patterns, which we term multi-arm compositional generalization. We also construct a benchmark in which test-time collaboration patterns are absent in training set. Across simulation and real-world evaluations, prior state-of-the-art VLAs largely fail under these unseen collaborations, while MA-VLA consistently succeeds. These results indicate that structured, per-arm atomic action assignment offers a practical route to scalable generalization in multi-arm embodied systems. Code, models, and data are available at https://github.com/zhangzaibin/future-robots

## TL;DR

Multi-arm collaboration is becoming a core capability in embodied manipulation. Recent vision-language-action (VLA) models integrate perception, language, and control, but most represent language as a single global instruction and do not provide an explicit mechanism for assigning and composing arm-specific behaviors.

## Related
<!-- [[other-paper-citekey]] -->
