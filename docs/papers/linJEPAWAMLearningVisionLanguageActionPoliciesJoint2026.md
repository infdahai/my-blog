---
citekey: "linJEPAWAMLearningVisionLanguageActionPoliciesJoint2026"
title: "JEPA-WAM: Learning Vision-Language-Action Policies with Joint-Embedding World Modeling"
authors: ["Yihan Lin", "Jiawei He", "Shifeng Bao", "Chen Zhao", "Yang Li", "Xiaobo Wang", "Yan Wang", "Cheng Chi", "Jing Zhang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.09381"
doi: "10.48550/arXiv.2608.09381"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# JEPA-WAM: Learning Vision-Language-Action Policies with Joint-Embedding World Modeling

> Yihan Lin, Jiawei He, Shifeng Bao, Chen Zhao, Yang Li, Xiaobo Wang, Yan Wang, Cheng Chi, Jing Zhang · 2026
> [arXiv](https://arxiv.org/abs/2608.09381) · [PDF](https://arxiv.org/pdf/2608.09381)

## Abstract

Robust robot control benefits from explicitly modeling state transitions, but video-generation world action models (WAMs) introduce substantial deployment cost. Existing latent WAMs avoid explicit future generation, but often compress predictive representations or separate predictive modeling from the representations used for action generation. We introduce JEPA-WAM, a latent WAM built in a pretrained V-JEPA space, which couples latent transition prediction with continuous action generation through a shared predictor. JEPA-WAM predicts a spatially structured joint current-future target that captures task-shared visual temporal structure between current and future observations, while preserving dense patch-level correspondence. Through the shared predictor, transition supervision directly shapes the backbone, from which dedicated representations are extracted for action prediction. The same design can also be instantiated in pretrained VLA policies while preserving their original perception and action pathways. On LIBERO-Plus, JEPA-WAM achieves 79.2%, the best result without large-scale robot-policy pretraining, while its pretrained $π_{0.5}$ instantiation reaches 86.3%, achieving the best overall performance. Experiments on RoboTwin 2.0 and real-world bimanual manipulation further demonstrate strong generalization under visual and spatial shifts.

## TL;DR

Robust robot control benefits from explicitly modeling state transitions, but video-generation world action models (WAMs) introduce substantial deployment cost. Existing latent WAMs avoid explicit future generation, but often compress predictive representations or separate predictive modeling from the representations used for action generation.

## Related
<!-- [[other-paper-citekey]] -->
