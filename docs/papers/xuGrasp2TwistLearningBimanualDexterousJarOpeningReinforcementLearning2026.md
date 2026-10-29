---
citekey: "xuGrasp2TwistLearningBimanualDexterousJarOpeningReinforcementLearning2026"
title: "Grasp2Twist: Learning Bimanual Dexterous Jar Opening by Reinforcement Learning"
authors: ["Mo Xu", "Yunfu Deng", "Jianuo Wang", "Josiah Hanna", "Bilge Mutlu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.32064"
doi: "10.48550/arXiv.2609.32064"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-29
---

# Grasp2Twist: Learning Bimanual Dexterous Jar Opening by Reinforcement Learning

> Mo Xu, Yunfu Deng, Jianuo Wang, Josiah Hanna, Bilge Mutlu · 2026
> [arXiv](https://arxiv.org/abs/2609.32064) · [PDF](https://arxiv.org/pdf/2609.32064)

## Abstract

This paper presents Grasp2Twist, a bimanual dexterous manipulation system that learns to grasp and twist open jar lids using reinforcement learning. Learning this task raises three challenges: learning a unified policy for a multi-stage task, sustaining lid twisting, and sim-to-real transfer. To address the first challenge, we introduce a continuous enclosure measure to guide grasp formation and a binary enclosure indicator to guide the grasp-to-twist transition for unified policy learning. We derive both from the geometric relationship between the object center and the convex hull formed by the hand's palm and fingertips. Kinematic constraints limit how far the hand can rotate the lid with fixed contacts, so sustained twisting requires finger contact reconfiguration. We use a three-stage curriculum to facilitate exploration of these contact changes and also improve robustness for sim-to-real transfer. With our approach, the learned policy demonstrates finger gaiting, reconfiguring hand-object contacts to sustain lid rotation. It transfers zero-shot to the physical system and achieves an 88% task success rate across six household containers, including peanut-butter, vitamin, and instant-coffee jars. Ablations further validate the roles of the geometric enclosure in grasp formation and the curriculum in contact-reconfiguration exploration.

## TL;DR

This paper presents Grasp2Twist, a bimanual dexterous manipulation system that learns to grasp and twist open jar lids using reinforcement learning. Learning this task raises three challenges: learning a unified policy for a multi-stage task, sustaining lid twisting, and sim-to-real transfer.

## Related
<!-- [[other-paper-citekey]] -->
