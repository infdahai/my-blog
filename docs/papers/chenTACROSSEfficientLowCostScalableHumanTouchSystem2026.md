---
citekey: "chenTACROSSEfficientLowCostScalableHumanTouchSystem2026"
title: "TACROSS: An Efficient and Low-Cost Scalable Human Touch System Across Heterogeneous Tactile Sensors for Dexterous Robot Learning"
authors: ["Bo Chen", "Huanzhang Hu", "Junyang Ma", "Bo Yue", "Fangdi Yu", "Haijier Chen", "Xianxin Lai", "Shuyu Pan", "Zhen Yang", "Xiaoquan Sun", "Wenze Cui", "Zhongliang Jiang", "Shaopeng Liu", "Jiayu Chen"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.11945"
doi: "10.48550/arXiv.2610.11945"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-10
---

# TACROSS: An Efficient and Low-Cost Scalable Human Touch System Across Heterogeneous Tactile Sensors for Dexterous Robot Learning

> Bo Chen, Huanzhang Hu, Junyang Ma, Bo Yue, Fangdi Yu, Haijier Chen, Xianxin Lai, Shuyu Pan, Zhen Yang, Xiaoquan Sun, Wenze Cui, Zhongliang Jiang, Shaopeng Liu, Jiayu Chen · 2026
> [arXiv](https://arxiv.org/abs/2610.11945) · [PDF](https://arxiv.org/pdf/2610.11945)

## Abstract

Collecting tactile demonstrations on robots is costly and slow, motivating the use of lower-cost human tactile gloves for scalable data collection. However, human capacitive/piezoresistive gloves and robotic tactile sensors differ fundamentally in transduction principle, sensor layout, spatial resolution, and dynamic response, making alignment of raw sensor channels ill-posed. To address this problem, we present TACROSS, a scalable system for learning from human touch and transferring it to robots that bridges this heterogeneity by aligning tactile streams at the level of contact events rather than raw sensor values. The hardware component of TACROSS integrates a piezoresistive glove with five layers and a cost of USD 10.86 with 285 sensing points. To align contact semantics, we design canonicalizers and residual adapters that map heterogeneous signals into a shared tactile latent with 256 dimensions via a temporal Transformer with attention across fingers. We further introduce a robot-grounded policy learning scheme in which robot demonstrations provide the sole source of ground-truth action supervision, while human demonstrations support tactile representation learning and provide confidence-weighted auxiliary supervision through valid retargeted hand targets. We evaluate our system on four contact-rich manipulation tasks. Compared to conventional teleoperation, our proposed system achieves a 3.5-fold efficiency improvement while reducing demonstration acquisition equipment cost by 95.7%. We will open-source the TACROSS hardware and software system and publicly release a tactile dataset comprising over 150 hours of recordings. Project page: https://tacross-touch-project.github.io/.

## TL;DR

Collecting tactile demonstrations on robots is costly and slow, motivating the use of lower-cost human tactile gloves for scalable data collection. However, human capacitive/piezoresistive gloves and robotic tactile sensors differ fundamentally in transduction principle, sensor layout, spatial resolution, and dynamic response, making alignment of raw sensor channels ill-posed.

## Related
<!-- [[other-paper-citekey]] -->
