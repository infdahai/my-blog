---
citekey: "daiCARDContactAnchoredRetargetingDexterousManipulation2026"
title: "CARD: Contact-Anchored Retargeting for Dexterous Manipulation"
authors: ["Cunxi Dai", "Botao He", "Francois R Hogan", "Wei Pan", "Rao Fu", "Wen-Han Hsieh", "Ruoshi Liu", "Jitendra Malik", "Guanya Shi", "Akash Sharma"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.36539"
doi: "10.48550/arXiv.2610.36539"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-28
---

# CARD: Contact-Anchored Retargeting for Dexterous Manipulation

> Cunxi Dai, Botao He, Francois R Hogan, Wei Pan, Rao Fu, Wen-Han Hsieh, Ruoshi Liu, Jitendra Malik, Guanya Shi, Akash Sharma · 2026
> [arXiv](https://arxiv.org/abs/2610.36539) · [PDF](https://arxiv.org/pdf/2610.36539)

## Abstract

Humans are dexterous, but traditional data collection paradigms such as teleoperation, kinesthetic teaching, and wearable exoskeletons force humans to act through the robot embodiment, bottlenecking their dexterity. Retargeting can avoid this. However, existing methods purely translate kinematics and ignore the real-world contact dynamics essential for task success. We present CARD: Contact-Anchored Retargeting for Dexterous Manipulation, a simulator and object-free framework that retargets human demonstrations to robot actions by explicitly preserving contact force targets. CARD unifies human data sources including video, motion capture, and tactile gloves via a shared hand--contact representation and generates explicit contact force targets in addition to kinematics. To maintain these contact targets during hardware open-loop replay, CARD also introduces a tactile tracking controller. For video which does not contain an explicit tactile source, we present Vid-HACO, our video-to-contact model that sets a new state of the art. Across our video, glove, motion-capture data and the GRAB dataset, CARD maintains contact on $43$--$78\%$ of contact frames, while kinematic and object-aware retargeting methods maintain contact on $<10\%$ and $22.5\%$ of the frames respectively. Further, integrating our formulation into physics-based retargeting improves strict task success from 12\% to 32\% on GRAB dataset. Finally, we show that our tactile tracker is critical to reproduce demonstrated forces during hardware replay. These results establish that contact preservation via CARD is a scalable interface for transferring human dexterity to robots.

## TL;DR

Humans are dexterous, but traditional data collection paradigms such as teleoperation, kinesthetic teaching, and wearable exoskeletons force humans to act through the robot embodiment, bottlenecking their dexterity. Retargeting can avoid this.

## Related
<!-- [[other-paper-citekey]] -->
