---
citekey: "dongAquaBEVMonocularUnderwaterBEVOccupancy3DSonarSupervision2026"
title: "AquaBEV: Monocular Underwater BEV Occupancy with 3D Sonar Supervision"
authors: ["Trung Tien Dong", "Shengji Jin", "Chen Chen", "Yi Sheng", "Xiaomin Lin"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.04411"
doi: "10.48550/arXiv.2609.04411"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-08
---

# AquaBEV: Monocular Underwater BEV Occupancy with 3D Sonar Supervision

> Trung Tien Dong, Shengji Jin, Chen Chen, Yi Sheng, Xiaomin Lin · 2026
> [arXiv](https://arxiv.org/abs/2609.04411) · [PDF](https://arxiv.org/pdf/2609.04411)

## Abstract

Autonomous underwater robots are widely used for exploration, monitoring, and inspection, where safe navigation depends on understanding the surrounding free and occupied space. Bird's eye view (BEV) occupancy provides such a representation, but predicting it from a single underwater RGB image is difficult due to limited, unreliable geometric cues from appearance alone. 3D imaging sonar offers complementary geometric measurements to supervise this task. We introduce AquaBEV, a monocular underwater occupancy model that predicts local BEV occupancy from a single RGB image, using paired 3D imaging sonar as geometric supervision during training. AquaBEV maps visual features into a calibration free polar representation and applies causal decoding along the range dimension before reconstructing the prediction in Cartesian BEV coordinates. A controlled underwater occupancy benchmark was established, adapting representative occupancy methods to the same RGB to sonar task under a unified protocol. AquaBEV achieves 31.4 Visible IoU and 38.6 Observed IoU, 4.0% and 4.3% relative improvements over the strongest transferred baseline.

## TL;DR

Autonomous underwater robots are widely used for exploration, monitoring, and inspection, where safe navigation depends on understanding the surrounding free and occupied space. Bird's eye view (BEV) occupancy provides such a representation, but predicting it from a single underwater RGB image is difficult due to limited, unreliable geometric cues from appearance alone.

## Related
<!-- [[other-paper-citekey]] -->
