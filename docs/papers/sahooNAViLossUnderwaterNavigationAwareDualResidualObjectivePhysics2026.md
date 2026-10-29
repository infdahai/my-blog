---
citekey: "sahooNAViLossUnderwaterNavigationAwareDualResidualObjectivePhysics2026"
title: "NAViLoss: An Underwater Navigation-Aware Dual-Residual Objective for Physics-Consistent Learning"
authors: ["Arup Kumar Sahoo", "Itzik Klein"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.09690"
doi: "10.48550/arXiv.2610.09690"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-10
---

# NAViLoss: An Underwater Navigation-Aware Dual-Residual Objective for Physics-Consistent Learning

> Arup Kumar Sahoo, Itzik Klein · 2026
> [arXiv](https://arxiv.org/abs/2610.09690) · [PDF](https://arxiv.org/pdf/2610.09690)

## Abstract

Autonomous underwater vehicles (AUVs) commonly rely on inertial navigation systems (INS) aided by Doppler velocity logs (DVLs) for reliable underwater navigation. Accurate DVL velocity estimation is therefore essential for successful operation. Recent learning-based methods have demonstrated improved DVL velocity estimation, particularly under degraded measurement conditions. However, their training objectives typically rely on conventional regression losses that are highly sensitive to large residuals and corrupted observations. Additionally, they do not explicitly account for the physical consistency and measurement uncertainty associated with the underlying sensing process. To address these limitations, this paper introduces navigation-aware loss (NAViLoss), a robust and uncertainty-aware objective function for learning-based AUV velocity estimation. NAViLoss jointly penalizes the velocity-estimation residual in the navigation-state domain and the beam-consistency residual in the DVL measurement domain. Its bounded formulation limits the influence of large residuals, while an adaptive mechanism regulates the uncertainty in beam geometry. Furthermore, NAViLoss is integrated with a DeepONet architecture to form a novel NAVi-DeepONet model for seamless estimation of an underwater vehicle's velocity. Lastly, our model is evaluated using approximately 10,000m of semi-synthetic AUV experimental data collected during multiple real-world sea trials. Experimental results demonstrate a 44% improvement in velocity-estimation accuracy compared with conventional and learning-based baselines. These results demonstrate the effectiveness of navigation-aware and uncertainty-adaptive loss design for robust learning-based underwater velocity estimation.

## TL;DR

Autonomous underwater vehicles (AUVs) commonly rely on inertial navigation systems (INS) aided by Doppler velocity logs (DVLs) for reliable underwater navigation. Accurate DVL velocity estimation is therefore essential for successful operation.

## Related
<!-- [[other-paper-citekey]] -->
