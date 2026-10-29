---
citekey: "zhangXWBCCrossEmbodimentFoundationModelHumanoidWhole2026"
title: "X-WBC: A Cross-Embodiment Foundation Model for Humanoid Whole-Body Control"
authors: ["Juntong Zhang", "Chun Gu", "Li Zhang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.15213"
doi: "10.48550/arXiv.2609.15213"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-16
---

# X-WBC: A Cross-Embodiment Foundation Model for Humanoid Whole-Body Control

> Juntong Zhang, Chun Gu, Li Zhang · 2026
> [arXiv](https://arxiv.org/abs/2609.15213) · [PDF](https://arxiv.org/pdf/2609.15213)

## Abstract

Scaling humanoid whole-body control toward general-purpose deployment requires large human motion corpora and training experience shared across robot bodies. Existing methods usually train one policy per robot, leaving motion experience isolated across embodiments. We introduce X-WBC, a cross-embodiment foundation framework that separates relatively shared human motion semantics from embodiment-specific physical execution. Human-centered command tokens align full human motion, robot reference motion, and sparse VR observations. A causal Transformer learns reusable temporal structure from mixed multi-robot rollouts, while lightweight robot-specific modules map the shared representation to each robot's proprioception and action space. Across nine simulated embodiments, external motions, and four real robots, experiments show that joint training improves tracking, the aligned representation supports consistent control across command sources, and the learned policy remains competitive beyond the training corpus. These results support heterogeneous humanoids as joint data sources and establish cross-embodiment joint training as a practical route toward whole-body control foundation models.

## TL;DR

Scaling humanoid whole-body control toward general-purpose deployment requires large human motion corpora and training experience shared across robot bodies. Existing methods usually train one policy per robot, leaving motion experience isolated across embodiments.

## Related
<!-- [[other-paper-citekey]] -->
