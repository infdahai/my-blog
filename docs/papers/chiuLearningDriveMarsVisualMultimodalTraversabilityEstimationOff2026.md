---
citekey: "chiuLearningDriveMarsVisualMultimodalTraversabilityEstimationOff2026"
title: "Learning to Drive on Mars: Visual Multimodal Traversability Estimation for Off-World Navigation"
authors: ["Darren Chiu", "Cole Wilson", "Andrei Tumbar", "Gaurav S. Sukhatme", "Steven Myint"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.24952"
doi: "10.48550/arXiv.2609.24952"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-23
---

# Learning to Drive on Mars: Visual Multimodal Traversability Estimation for Off-World Navigation

> Darren Chiu, Cole Wilson, Andrei Tumbar, Gaurav S. Sukhatme, Steven Myint · 2026
> [arXiv](https://arxiv.org/abs/2609.24952) · [PDF](https://arxiv.org/pdf/2609.24952)

## Abstract

Autonomous navigation on Mars requires vehicles to distinguish between traversable terrains across diverse and visually challenging environments. However, progress in learning-based navigation for off-world environments has been limited by the lack of large-scale datasets. Since landing in Jezero Crater, the Mars 2020 Perseverance rover has traversed terrain ranging from sandy dunes, rocky patches, and flat bedrocks. As a result, this paper presents a dataset spanning 500 sols and 45km of trajectories driven by both human operators and the onboard planner, ENav. Our dataset contains grayscale stereo image pairs, poses, accelerometer readings, rocker-bogie angles, and estimates of tilt and wheel slip. Building on this dataset, we introduce an uncertainty-aware traversability-estimation framework that learns terrain representations from multimodal driving experience. We compare our proposed method against existing approaches on the Mars 2020 dataset and show that our method achieves an AUROC of 0.874 and an F1 score of 0.758, outperforming the strongest baseline by 0.058 and 0.156, respectively, while also achieving the highest average precision and recall. Finally, we show that the visual representations can be integrated into path planners, such as ENav, on a physical rover test bed. Videos, code, and the M2020 dataset will be available at https://darren-chiu.github.io/learning-to-drive-on-mars.

## TL;DR

Autonomous navigation on Mars requires vehicles to distinguish between traversable terrains across diverse and visually challenging environments. However, progress in learning-based navigation for off-world environments has been limited by the lack of large-scale datasets.

## Related
<!-- [[other-paper-citekey]] -->
