---
citekey: "fechnerVPRSpaceBenchmarkVisualPlaceRecognitionSpaceAnalog2026"
title: "VPR-Space: A Benchmark for Visual Place Recognition in Space Analog Domains"
authors: ["Richard Fechner", "Peer Neubert"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.35642"
doi: "10.48550/arXiv.2610.35642"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-28
---

# VPR-Space: A Benchmark for Visual Place Recognition in Space Analog Domains

> Richard Fechner, Peer Neubert · 2026
> [arXiv](https://arxiv.org/abs/2610.35642) · [PDF](https://arxiv.org/pdf/2610.35642)

## Abstract

Visual Place Recognition (VPR) is an important means for loop closure detection in visual Simultaneous Localization and Mapping (SLAM). While state-of-the-art VPR and SLAM approaches excel in urban and feature-rich natural environments, the vast and feature-poor environments of extraterrestrial surfaces like on the Moon or Mars pose severe challenges for existing approaches. This paper presents a novel benchmark, VPR-Space, to evaluate VPR capabilities on extraterrestrial surfaces. There are three contributions: (1) We collected sixteen VPR database-query datasets based on existing data from Space Analog Domains (SAD), terrestrial environments that resemble properties of the Moon or Mars. The collection includes a range of challenges regarding environment, viewpoint change, and illumination conditions. (2) To address the ill-posed nature of VPR, we propose a novel approach to generate the ground-truth information in VPR benchmarks. Instead of defining that a query and datbase image show the same place if and only if their camera poses are within fixed position and viewing direction thresholds, we propose to make the decision dependent on whether the match would be valuable in the downstream SLAM task. To avoid the overhead and restrictions of evaluating VPR in-the-loop within SLAM systems, we provide VPR ground-truth (GT) matrices based on the performance of an ensemble of state-of-the-art Relative Pose Estimators (RPE). Under this GT we require a VPR method to identify exactly those image pairs for which a subsequently applied RPE is expected to provide a valuable pose estimate in a SLAM context. (3) We evaluated nine state-of-the-art VPR approaches. The results show considerable room for improvement and indicate directions for future research. We provide a pre-release version of the dataset on github: $\texttt{https://github.com/rfechner/VPR-Space}$

## TL;DR

Visual Place Recognition (VPR) is an important means for loop closure detection in visual Simultaneous Localization and Mapping (SLAM). While state-of-the-art VPR and SLAM approaches excel in urban and feature-rich natural environments, the vast and feature-poor environments of extraterrestrial surfaces like on the Moon or Mars pose severe challenges for existing approaches.

## Related
<!-- [[other-paper-citekey]] -->
