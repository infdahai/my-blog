---
citekey: "chenSeeWhatINeedDreamWhatIWant2026"
title: "See What I Need, Dream What I Want: A Navigation Foundation Model on a Self-Constructed Representation Space"
authors: ["Jiawei Chen", "Yinxi Wang", "Zihan Yang", "Meijun Gao", "Yaowei Liu", "Shuming Zhang", "Zecheng Li", "Xiangju Mi", "Yuxuan Liu", "Runzhong Huang", "Tianlin Li", "Xun Zhang", "Zhengyang Wang", "Xu Miao", "Tong Yang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.31762"
doi: "10.48550/arXiv.2610.31762"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-27
---

# See What I Need, Dream What I Want: A Navigation Foundation Model on a Self-Constructed Representation Space

> Jiawei Chen, Yinxi Wang, Zihan Yang, Meijun Gao, Yaowei Liu, Shuming Zhang, Zecheng Li, Xiangju Mi, Yuxuan Liu, Runzhong Huang, Tianlin Li, Xun Zhang, Zhengyang Wang, Xu Miao, Tong Yang · 2026
> [arXiv](https://arxiv.org/abs/2610.31762) · [PDF](https://arxiv.org/pdf/2610.31762)

## Abstract

What visual representation should a navigation policy act on? Navigation policies built on vision foundation models largely leave representation design to the encoders' pretraining objectives. We present RepresentNav, a navigation foundation model built on a self-constructed representation space: a visual representation constructed by the policy's own objectives from vision foundation models. RepresentNav builds this space with Representation Residuals, a compact three-layer transformer that attends over features spanning the full depth of multiple complementary vision foundation models, so that the policy learns to see what it needs for navigation. In the same space it dreams what it wants: before every action a latent chain-of-thought predicts the representation of the scene a moment ahead. The dream is trained end-to-end with the policy as a joint-embedding predictive architecture (JEPA), with a next-representation prediction loss and a regularizer on its targets. RepresentNav sets a new state of the art on VLNVerse, VLN-CE R2R, EVT-Bench, and two point-goal benchmarks, and its gains carry over to a physical robot amid clutter and moving people. On VLNVerse fine-grained, RepresentNav achieves 83.80% success, outperforming the previous state of the art by 20.05 percentage points, and on EVT-Bench distracted tracking it reaches 85.5% with a single camera (+10.1). With the same encoders, the self-constructed space clearly outperforms concatenating their outputs and learns to weight their layers unevenly, and a dream in it cuts collisions by a quarter. A single dreamed latent decodes into the depth, semantics, and 3D occupancy of the scene a moment ahead, more accurately than pretrained encoders applied to the real future frame, although occupancy is never supervised, and the rollout tracks the robot's own motion over the next second: the dream emerges as a compact latent world model.

## TL;DR

What visual representation should a navigation policy act on? Navigation policies built on vision foundation models largely leave representation design to the encoders' pretraining objectives.

## Related
<!-- [[other-paper-citekey]] -->
