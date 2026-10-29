---
citekey: "zhengEdgeNativeTemporalGraphDualExpertInferenceDexterous2026"
title: "Edge-Native Temporal--Graph Dual-Expert Inference for Dexterous Grasp Classification"
authors: ["Jiajian Zheng", "Bin Zhang", "Wen Fan", "Yanan Liu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.14926"
doi: "10.48550/arXiv.2610.14926"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-15
---

# Edge-Native Temporal--Graph Dual-Expert Inference for Dexterous Grasp Classification

> Jiajian Zheng, Bin Zhang, Wen Fan, Yanan Liu · 2026
> [arXiv](https://arxiv.org/abs/2610.14926) · [PDF](https://arxiv.org/pdf/2610.14926)

## Abstract

Multi-finger hands contact objects at different times, so a global close command can overload early-contact fingers while others are still moving. Dense tactile arrays address this problem but add hardware, calibration, bandwidth, and computation. We present an edge-native pipeline that uses only built-in joint-angle and pre-use-calibrated actuator-load feedback to recognize the grasped object and predict an independent Stop event for each finger. Four samples and their first differences form a 4-by-20 contact-evolution window. At its core is a heterogeneous dual-expert architecture, termed DualExpert, that assigns complementary tasks to a Temporal Convolutional Network (TCN) and a Finger Graph Filter Network (FGFN). The TCN models short-term contact evolution and supplies all five Stop probabilities, while the FGFN encodes finger topology and contributes only to object classification. Fixed 0.7/0.3 class-probability fusion reaches 93.78\% trajectory-level classification accuracy on 225 held-out trials, improving the standalone TCN and FGFN by 4.00 and 2.22 percentage points, respectively. The TCN Stop path attains 95.25\% F1. The dataset contains 1,500 automatically collected trajectories from five object instances. In Flash deployment, mixed accelerator execution retains 93.78\% classification accuracy and 94.84\% Stop F1 with 2.890~ms mean inference time and 9.172~ms mean sample-to-stop latency. Across 50 physical trials, the system achieves 96.00\% recognition and 98.00\% grasp success while the complete embedded board draws approximately 0.80~W.

## TL;DR

Multi-finger hands contact objects at different times, so a global close command can overload early-contact fingers while others are still moving. Dense tactile arrays address this problem but add hardware, calibration, bandwidth, and computation.

## Related
<!-- [[other-paper-citekey]] -->
