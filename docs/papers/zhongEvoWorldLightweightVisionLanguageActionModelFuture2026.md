---
citekey: "zhongEvoWorldLightweightVisionLanguageActionModelFuture2026"
title: "Evo-World: A Lightweight Vision-Language-Action Model with Future Motion Prediction via Optical-Flow Supervision"
authors: ["Zile Zhong", "Yuxin Du", "Tao Lin", "Haoxiao Wang", "Wei Dai", "Binhua Zuo", "Bo Zhao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.12936"
doi: "10.48550/arXiv.2610.12936"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-13
---

# Evo-World: A Lightweight Vision-Language-Action Model with Future Motion Prediction via Optical-Flow Supervision

> Zile Zhong, Yuxin Du, Tao Lin, Haoxiao Wang, Wei Dai, Binhua Zuo, Bo Zhao · 2026
> [arXiv](https://arxiv.org/abs/2610.12936) · [PDF](https://arxiv.org/pdf/2610.12936)

## Abstract

Vision-language-action (VLA) models provide a unified framework for visual understanding, language grounding, and robot control, yet anticipating how the scene will evolve beyond the current observation can provide additional information for control. Action supervision alone does not explicitly encourage such anticipation, while future-image prediction entangles task-relevant motion with largely static appearance. To address these limitations, we introduce Evo-World, a lightweight VLA model that augments policy learning with future motion prediction through optical-flow supervision, thereby providing a task-relevant predictive signal focused on motion rather than appearance. We further design the training procedure to preserve these predictive representations during policy learning, regulating representation diversity while decoupling representation learning from action optimization. Across simulation benchmarks, Evo-World demonstrates strong performance, achieving a tier-averaged success rate of 91.1% on Meta-World MT50 , with a 13.0% relative improvement over the non-predictive baseline. On real-world AgileX robots, Evo-World outperforms the evaluated baselines across single-arm and bimanual manipulation tasks while using only 0.87B parameters and delivering lower GPU memory usage and higher inference efficiency. These results demonstrate that future motion prediction through optical-flow supervision provides an effective and lightweight approach to enhancing the predictive capabilities of VLA models.

## TL;DR

Vision-language-action (VLA) models provide a unified framework for visual understanding, language grounding, and robot control, yet anticipating how the scene will evolve beyond the current observation can provide additional information for control. Action supervision alone does not explicitly encourage such anticipation, while future-image prediction entangles task-relevant motion with largely static appearance.

## Related
<!-- [[other-paper-citekey]] -->
