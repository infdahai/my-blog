---
citekey: "zhangScaRFSLAMScaleConsistentReconstructionFeedForwardModels2026"
title: "ScaRF-SLAM: Scale-Consistent Reconstruction with Feed-Forward Models and Classical Visual SLAM"
authors: ["Yuhao Zhang", "Yifu Tao", "Frank Dellaert", "Maurice Fallon"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2606.00307"
doi: "10.48550/arXiv.2606.00307"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# ScaRF-SLAM: Scale-Consistent Reconstruction with Feed-Forward Models and Classical Visual SLAM

> Yuhao Zhang, Yifu Tao, Frank Dellaert, Maurice Fallon · 2026
> [arXiv](https://arxiv.org/abs/2606.00307) · [PDF](https://arxiv.org/pdf/2606.00307)

## Abstract

Recent works have explored unifying SLAM with geometric foundation models (GFMs). However, directly using GFM predictions for tracking is highly sensitive to model capability and uncertainty, as geometric inaccuracies in the predictions can adversely affect pose estimation. To address this limitation, we present a decoupled framework that integrates classical feature-based SLAM with GFMs, which achieves higher quality and more consistent dense reconstruction. In brief, we use classical visual SLAM for robust low-latency tracking and use GFMs exclusively for mapping. By anchoring mapping to poses produced by the SLAM module and optimizing across depth scales, the proposed design avoids propagating inaccuracies from GFM predictions into pose estimation while imposing geometric constraints on the reconstruction. The system builds submaps from multiple posed keyframes and enforces scale consistency via lightweight frame and submap scale optimization. It also performs projection-based point cloud fusion within each submap, and updates submaps online to reflect trajectory updates from the feature-based SLAM. To evaluate tracking and reconstruction of our method, we introduce a loop-rich, building-scale indoor dataset with accurate sensor trajectories and LiDAR ground-truth. Experiments show that our approach achieves superior trajectory accuracy while improving reconstruction precision by 10%-20% over existing methods, with about 2 cm reconstruction error per 10 m chunk on building-scale dataset. On large-scale outdoor datasets, it attains 10 cm error per 30 m chunk (w.r.t LiDAR ground-truth models). Code and dataset: https://github.com/ori-drs/ScaRF-SLAM

## TL;DR

Recent works have explored unifying SLAM with geometric foundation models (GFMs). However, directly using GFM predictions for tracking is highly sensitive to model capability and uncertainty, as geometric inaccuracies in the predictions can adversely affect pose estimation.

## Related
<!-- [[other-paper-citekey]] -->
