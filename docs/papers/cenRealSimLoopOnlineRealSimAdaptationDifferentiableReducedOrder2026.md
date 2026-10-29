---
citekey: "cenRealSimLoopOnlineRealSimAdaptationDifferentiableReducedOrder2026"
title: "RealSimLoop: Online Real-to-Sim Adaptation via Differentiable Reduced-Order Simulation with Vision Feedback"
authors: ["Zhihao Cen", "Chuhua Xian", "Hailin Sun", "Yuliang Liufu", "Zhen Zhang", "Xiangyu Chu", "Hongmin Cai", "Yunbo Zhang", "Guoxin Fang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.09828"
doi: "10.48550/arXiv.2609.09828"
tags: [paper, embodied-ai, "cs.CV", "cs.GR", "cs.RO"]
status: unread
rating:
created: 2026-09-11
---

# RealSimLoop: Online Real-to-Sim Adaptation via Differentiable Reduced-Order Simulation with Vision Feedback

> Zhihao Cen, Chuhua Xian, Hailin Sun, Yuliang Liufu, Zhen Zhang, Xiangyu Chu, Hongmin Cai, Yunbo Zhang, Guoxin Fang · 2026
> [arXiv](https://arxiv.org/abs/2609.09828) · [PDF](https://arxiv.org/pdf/2609.09828)

## Abstract

Real-world observations of deformable objects are often sparse or surface-level, while downstream tasks require hidden physical quantities such as internal deformation, stress fields, and interaction forces. Physics-based simulation can recover these quantities, but online real-to-sim adaptation remains challenging due to costly full-space optimization, limited feedback, and time-varying material properties. To address these challenges, we propose RealSimLoop, a differentiable framework for online real-to-sim adaptation using vision data as physical feedback. Our approach achieves quasi-real-time performance by executing differentiable simulation within a reduced-order neural subspace, drastically accelerating the optimization loop. We couple this efficient dynamics model with differentiable rendering, enabling direct gradient backpropagation that leverages high-fidelity pixel data to refine physical parameters such as material stiffness. Furthermore, by employing a sliding-window objective function, RealSimLoop enables robust online adaptation, allowing the system to track time-varying material properties and effectively bridge the real-to-sim gap arising from model reduction or unmodeled dynamics. Extensive experiments demonstrate that our method outperforms conventional offline methods, and we validate the framework's versatility in downstream applications, including external force prediction and 3D stress field reconstruction with novel view synthesis.

## TL;DR

Real-world observations of deformable objects are often sparse or surface-level, while downstream tasks require hidden physical quantities such as internal deformation, stress fields, and interaction forces. Physics-based simulation can recover these quantities, but online real-to-sim adaptation remains challenging due to costly full-space optimization, limited feedback, and time-varying material properties.

## Related
<!-- [[other-paper-citekey]] -->
