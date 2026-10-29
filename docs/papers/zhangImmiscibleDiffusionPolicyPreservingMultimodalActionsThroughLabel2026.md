---
citekey: "zhangImmiscibleDiffusionPolicyPreservingMultimodalActionsThroughLabel2026"
title: "Immiscible Diffusion Policy: Preserving Multimodal Robot Actions through Label-Free Noise Assignment"
authors: ["Xiao Zhang", "Yuxin Chen", "Zhixuan Liang", "Guojian Zhan", "Chenran Li", "Chenfeng Xu", "Masayoshi Tomizuka", "Yiheng Li"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.09369"
doi: "10.48550/arXiv.2610.09369"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-09
---

# Immiscible Diffusion Policy: Preserving Multimodal Robot Actions through Label-Free Noise Assignment

> Xiao Zhang, Yuxin Chen, Zhixuan Liang, Guojian Zhan, Chenran Li, Chenfeng Xu, Masayoshi Tomizuka, Yiheng Li · 2026
> [arXiv](https://arxiv.org/abs/2610.09369) · [PDF](https://arxiv.org/pdf/2610.09369)

## Abstract

When diffusion policies were first introduced, they were expected to recover multi-modal action distributions. However, we find this expectation does not always hold, as diffusion policies often collapse to a single modality even when we guarantee the balance of dataset modalities and exact within-batch symmetry. Our analysis indicates that independent action-noise pairing contributes to this failure by increasing mixing and crossing among diffusion paths, which can produce averaged denoising responses and suppress modality-specific behavior. This issue is especially severe in robot planning, where action spaces are dense and low-dimensional, significantly increasing such mixing and crossing. To alleviate this problem, we propose Immiscible Diffusion Policy, a label-free training-time add-on to diffusion policy that uses action-noise assignment to preserve relatively distinct noise-to-action routes without modifying the policy architecture or inference procedure. Across five simulated and two real-world humanoid manipulation tasks spanning state, RGB, and point-cloud observations, our method significantly improves the policy's preservation of action modalities while maintaining strong task performance. It increases the proportion of the non-dominant modality by 6.0x-14.6x across three two-modality tasks and recovers demonstrated modalities that are entirely absent from vanilla policy rollouts on both four-modality tasks. These results demonstrate that Immiscible Diffusion Policy provides a simple yet robust approach to preserving action multi-modality in general robot learning tasks.

## TL;DR

When diffusion policies were first introduced, they were expected to recover multi-modal action distributions. However, we find this expectation does not always hold, as diffusion policies often collapse to a single modality even when we guarantee the balance of dataset modalities and exact within-batch symmetry.

## Related
<!-- [[other-paper-citekey]] -->
