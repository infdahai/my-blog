---
citekey: "huangChairNavCrossEmbodimentPreTrainingPersonalizationLongHorizon2026"
title: "ChairNav: Cross-Embodiment Pre-training and Personalization for Long-Horizon Wheelchair Navigation"
authors: ["Junhua Huang", "Zhizheng Liu", "Honglin He", "Xiang Zhang", "Bolei Zhou"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.24012"
doi: "10.48550/arXiv.2610.24012"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-22
---

# ChairNav: Cross-Embodiment Pre-training and Personalization for Long-Horizon Wheelchair Navigation

> Junhua Huang, Zhizheng Liu, Honglin He, Xiang Zhang, Bolei Zhou · 2026
> [arXiv](https://arxiv.org/abs/2610.24012) · [PDF](https://arxiv.org/pdf/2610.24012)

## Abstract

Developing autonomous electric wheelchairs capable of long-horizon sidewalk navigation is critical for accessible personal mobility, yet existing approaches either focus on indoor map-based navigation or rely on expensive, complex sensor stacks to achieve full autonomy. In this work, we propose to tackle outdoor sidewalk navigation by leveraging visual navigation foundation models and large-scale navigation datasets, which offer strong generalization using lightweight hardware. To this end, we present ChairNav, a novel framework that adapts a general visual navigation model into a personalized electric wheelchair navigation system using a three-stage data pyramid. To address the scarcity of in-domain data, ChairNav first pre-trains on large-scale cross-embodiment datasets transformed into the wheelchair domain, followed by mid-training on a small number of wheelchair demonstrations to eliminate remaining domain gaps. Finally, a post-training stage refines the deployed model from user interventions to personalize its behavior. We deploy ChairNav on a commercial electric wheelchair equipped with an RGB-D camera and an onboard NVIDIA Jetson compute module. Experimental results validate the effectiveness of each stage in our data pyramid: pre-training reduces lateral ADE by 18%, and post-training increases the mean distance between user interventions from 29.2 m to 57.4 m. Further evaluation on kilometer-scale urban sidewalk routes shows that our system operates autonomously for 93.4% of total driving time, demonstrating its potential for everyday accessible mobility. Demo video and more details are at https://vail.cs.ucla.edu/ChairNav/.

## TL;DR

Developing autonomous electric wheelchairs capable of long-horizon sidewalk navigation is critical for accessible personal mobility, yet existing approaches either focus on indoor map-based navigation or rely on expensive, complex sensor stacks to achieve full autonomy. In this work, we propose to tackle outdoor sidewalk navigation by leveraging visual navigation foundation models and large-scale navigation datasets, which offer strong generalization using lightweight hardware.

## Related
<!-- [[other-paper-citekey]] -->
