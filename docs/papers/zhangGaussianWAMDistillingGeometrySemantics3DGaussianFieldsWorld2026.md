---
citekey: "zhangGaussianWAMDistillingGeometrySemantics3DGaussianFieldsWorld2026"
title: "GaussianWAM: Distilling Geometry and Semantics from 3D Gaussian Fields into World-Action Models"
authors: ["Zijian Zhang", "Yuqing Jiang", "Weitao Zhou", "Minglei Li", "Jinhao Zhang", "Yao Mu", "Xiaofan Li", "Hao Zhao", "Haibao Yu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.24714"
doi: "10.48550/arXiv.2608.24714"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-26
---

# GaussianWAM: Distilling Geometry and Semantics from 3D Gaussian Fields into World-Action Models

> Zijian Zhang, Yuqing Jiang, Weitao Zhou, Minglei Li, Jinhao Zhang, Yao Mu, Xiaofan Li, Hao Zhao, Haibao Yu · 2026
> [arXiv](https://arxiv.org/abs/2608.24714) · [PDF](https://arxiv.org/pdf/2608.24714)

## Abstract

World-Action Models (WAMs) jointly learn future visual prediction and action generation, using video dynamics as a representation-learning signal for robotic manipulation. However, their video latents are primarily optimized for visual prediction and are not explicitly encouraged to preserve cross-view geometric structure or spatially localized, object-relevant semantics. We propose \textbf{GaussianWAM}, a training-time representation-enhancement framework that organizes geometric and semantic supervision through a 3D Gaussian field. Given synchronized multi-view observations, frozen geometry and vision foundation models provide depth, camera parameters, and dense semantic features. GaussianWAM binds these heterogeneous signals to shared Gaussian primitives and renders spatially aligned semantic, depth, and coverage targets, which are distilled into the current-observation representations of the WAM. All teacher models, Gaussian components, and auxiliary prediction heads are removed after training, leaving the original WAM inference path without additional modules or forward computation. On LIBERO-Plus, GaussianWAM improves FastWAM from 52.05\% to 71.29\% and Cosmos Policy from 71.52\% to 77.30\%. Direct CLIP and VGGT distillation already establishes a strong FastWAM baseline of 69.37\%, while Gaussian-field unification further improves it to 71.29\%, supporting the benefit of spatially organizing heterogeneous teacher signals. GaussianWAM also improves performance on standard LIBERO and shows positive transfer trends on RoboTwin and real-world manipulation. These results suggest that training-time Gaussian distillation provides a practical way to inject geometry- and semantics-related supervision into WAM representations without changing their deployment architecture.

## TL;DR

World-Action Models (WAMs) jointly learn future visual prediction and action generation, using video dynamics as a representation-learning signal for robotic manipulation. However, their video latents are primarily optimized for visual prediction and are not explicitly encouraged to preserve cross-view geometric structure or spatially localized, object-relevant semantics.

## Related
<!-- [[other-paper-citekey]] -->
