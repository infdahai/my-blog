---
citekey: "yuPoseAwareModelingMitigatePoseRelatedArtifactsTactile2026"
title: "Pose-Aware Modeling to Mitigate Pose-Related Artifacts in Tactile Gloves"
authors: ["Tianhong Catherine Yu", "Ziyi Kou", "Mia Huang", "Taylor Niehues", "Yiyue Luo", "Li Guan", "Dingtian Zhang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2607.22964"
doi: "10.48550/arXiv.2607.22964"
tags: [paper, embodied-ai, "cs.HC", "cs.RO"]
status: unread
rating:
created: 2026-09-07
---

# Pose-Aware Modeling to Mitigate Pose-Related Artifacts in Tactile Gloves

> Tianhong Catherine Yu, Ziyi Kou, Mia Huang, Taylor Niehues, Yiyue Luo, Li Guan, Dingtian Zhang · 2026
> [arXiv](https://arxiv.org/abs/2607.22964) · [PDF](https://arxiv.org/pdf/2607.22964)

## Abstract

Tactile gloves digitize contact and force during hand-object interactions, enabling robotics applications in dexterous manipulation, teleoperation, and learning from demonstration. To preserve hand dexterity and capture the nuances of natural interactions, these gloves and the integrated tactile sensors are designed to be soft, flexible, and comfortable. However, such flexible sensors are sensitive not only to contact forces but also unavoidably to hand pose changes, resulting in pose-related artifacts (PRAs). PRAs are especially problematic in the low-force range, resulting in misdetections or late-onset detections of contact, which raises the minimum detectable force (MDF) of the glove. In this work, we characterize the PRAs in relation to pose and force. Building on these insights, we introduce a glove-agnostic algorithmic framework that leverages hand pose information, which is increasingly available, to mitigate PRAs without glove modifications. Our pose-aware force estimation model augments tactile-to-force pipelines with a residual prediction branch that explicitly accounts for pose-induced sensor deformations. We validate our approach across 3 glove designs and 15 users, reducing MDF by 10.4%, 12.2%, and 18.3%, with consistent improvements across all evaluated metrics. This method provides a practical path to improving the usability of tactile gloves in data collection and diverse robotic applications.

## TL;DR

Tactile gloves digitize contact and force during hand-object interactions, enabling robotics applications in dexterous manipulation, teleoperation, and learning from demonstration. To preserve hand dexterity and capture the nuances of natural interactions, these gloves and the integrated tactile sensors are designed to be soft, flexible, and comfortable.

## Related
<!-- [[other-paper-citekey]] -->
