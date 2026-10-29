---
citekey: "chenMoPACoordinatedMobileManipulationSubsystemSpecificPerceptionAlignment2026"
title: "MoPA: Coordinated Mobile Manipulation via Subsystem-Specific Perception Alignment"
authors: ["Guangyu Chen", "Qiwei Liang", "Shaolong Zhu", "Tianxing Chen", "Zikuan Xiao", "Yifan Xie", "Lingfeng Zhang", "Ping Luo", "Renjing Xu", "Wenbo Ding"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.12081"
doi: "10.48550/arXiv.2609.12081"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-15
---

# MoPA: Coordinated Mobile Manipulation via Subsystem-Specific Perception Alignment

> Guangyu Chen, Qiwei Liang, Shaolong Zhu, Tianxing Chen, Zikuan Xiao, Yifan Xie, Lingfeng Zhang, Ping Luo, Renjing Xu, Wenbo Ding · 2026
> [arXiv](https://arxiv.org/abs/2609.12081) · [PDF](https://arxiv.org/pdf/2609.12081)

## Abstract

Mobile manipulation requires perceptual evidence at different spatial scales for base motion and arm control, while the two action modalities remain kinematically coupled. Existing policies often employ specialized action generation for different subsystems but condition heterogeneous action branches on a shared perceptual representation, leaving subsystem-specific perception-action correspondence implicit. We present MoPA, a framework that aligns perceptual conditioning with mobility and manipulation while preserving coordination at the action level. Dual Perceptual Streams employ two mutually masked query banks to extract separate perceptual representations from a shared vision-language context. Perception2Action Adaptation jointly updates each query bank and its corresponding action stream at every layer of a structured Mixture-of-Transformers decoder, while enabling information exchange between the two action streams. Coupled conditional flow matching learns a joint vector field for coordinated generation of both action chunks. On the ManiSkill-HAB benchmark, MoPA achieves state-of-the-art performance across all three task suites. Across four real-world tasks, MoPA achieves a mean full-task success rate of 76.3%, outperforming the best baseline by 12.5 percentage points. Ablation studies and further analyses validate the effectiveness of the proposed design. Website is available at: https://mopa-policy.github.io/.

## TL;DR

Mobile manipulation requires perceptual evidence at different spatial scales for base motion and arm control, while the two action modalities remain kinematically coupled. Existing policies often employ specialized action generation for different subsystems but condition heterogeneous action branches on a shared perceptual representation, leaving subsystem-specific perception-action correspondence implicit.

## Related
<!-- [[other-paper-citekey]] -->
