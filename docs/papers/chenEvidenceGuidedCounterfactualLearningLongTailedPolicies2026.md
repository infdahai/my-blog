---
citekey: "chenEvidenceGuidedCounterfactualLearningLongTailedPolicies2026"
title: "Evidence-Guided Counterfactual Learning for Long-Tailed Robotic Policies"
authors: ["Weiwei Chen", "Chenghao Xu", "Meiling Yu", "Xu Yang", "Cheng Deng"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.12861"
doi: "10.48550/arXiv.2610.12861"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-13
---

# Evidence-Guided Counterfactual Learning for Long-Tailed Robotic Policies

> Weiwei Chen, Chenghao Xu, Meiling Yu, Xu Yang, Cheng Deng · 2026
> [arXiv](https://arxiv.org/abs/2610.12861) · [PDF](https://arxiv.org/pdf/2610.12861)

## Abstract

In the practical deployment of vision--language--action policies, handling long-tailed task distributions is a common challenge due to the highly imbalanced composition of robot demonstration datasets. To investigate this issue, we study the head-task action bias in shared robot policies, particularly focusing on its relationship with task-specific visual evidence. Our experimental analysis shows that, when the visual evidence required by a tail task is insufficient, the policy increasingly falls back on action patterns reinforced by data-rich head tasks, resulting in degraded performance on under-represented tasks. Motivated by this observation, we propose Evidence-Guided Counterfactual Learning, a training framework for long-tailed robot policies. Our method identifies decision-relevant visual evidence using instruction-related and action-related signals, and constructs counterfactual observations by removing the selected evidence. The resulting counterfactual predictions are used to strengthen the association among task instructions, visual evidence, and actions, with the supervision adaptively adjusted according to the number of demonstrations available for each task. The proposed framework requires neither additional training data nor region-level annotations and incurs no additional computation during deployment. Extensive experiments across simulated benchmarks, different VLA architectures, and real-world robot platforms demonstrate that our method robustly and consistently improves long-tailed robot policy learning, particularly for tail tasks, while maintaining reliable performance on head tasks.

## TL;DR

In the practical deployment of vision--language--action policies, handling long-tailed task distributions is a common challenge due to the highly imbalanced composition of robot demonstration datasets. To investigate this issue, we study the head-task action bias in shared robot policies, particularly focusing on its relationship with task-specific visual evidence.

## Related
<!-- [[other-paper-citekey]] -->
