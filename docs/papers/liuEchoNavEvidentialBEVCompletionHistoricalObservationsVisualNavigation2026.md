---
citekey: "liuEchoNavEvidentialBEVCompletionHistoricalObservationsVisualNavigation2026"
title: "EchoNav: Evidential BEV Completion from Historical Observations for Visual Navigation"
authors: ["Diwen Liu", "Yiyang Shao", "Borui Wang", "Chi Zhang", "Yunhui Liu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.27616"
doi: "10.48550/arXiv.2610.27616"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-22
---

# EchoNav: Evidential BEV Completion from Historical Observations for Visual Navigation

> Diwen Liu, Yiyang Shao, Borui Wang, Chi Zhang, Yunhui Liu · 2026
> [arXiv](https://arxiv.org/abs/2610.27616) · [PDF](https://arxiv.org/pdf/2610.27616)

## Abstract

Visual navigation in cluttered environments requires robots to recover previously observed structure and infer obstacles and free space that remain occluded. We present a framework that combines temporal aggregation and occupancy completion in an evidential bird's-eye-view (BEV) representation predicted from short RGB sequences. A decoder adapts frozen VGGT-Omega features and combines historical residual proposals using cellwise weights and a learned no-update option. The BEV predictor produces a local map in the latest ego frame without depth or camera-pose inputs or explicit geometric warping. The evidential model treats observed free space separately and predicts occupancy with associated confidence across the remaining supported region. We train the predictor on simulated RGB sequences paired with complete and visibility-masked occupancy annotations. Our experiments evaluate navigation in simulation and on a wheeled robot, with additional demonstrations on quadruped and humanoid robots. In simulated sequential two-goal navigation, our system achieves 89.6% success, outperforming the strongest evaluated baseline by 32.5 percentage points. Across 60 wheeled-robot trials in 20 scenes, it achieves 73.3% success, compared with 33.3% for the strongest evaluated baseline.

## TL;DR

Visual navigation in cluttered environments requires robots to recover previously observed structure and infer obstacles and free space that remain occluded. We present a framework that combines temporal aggregation and occupancy completion in an evidential bird's-eye-view (BEV) representation predicted from short RGB sequences.

## Related
<!-- [[other-paper-citekey]] -->
