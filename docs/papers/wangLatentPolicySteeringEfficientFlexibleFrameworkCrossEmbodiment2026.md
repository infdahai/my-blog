---
citekey: "wangLatentPolicySteeringEfficientFlexibleFrameworkCrossEmbodiment2026"
title: "Latent Policy Steering: An Efficient and Flexible Framework for Cross-Embodiment Transfer"
authors: ["Yiqi Wang", "Mrinal Verghese", "Jeff Schneider"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.22521"
doi: "10.48550/arXiv.2609.22521"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-22
---

# Latent Policy Steering: An Efficient and Flexible Framework for Cross-Embodiment Transfer

> Yiqi Wang, Mrinal Verghese, Jeff Schneider · 2026
> [arXiv](https://arxiv.org/abs/2609.22521) · [PDF](https://arxiv.org/pdf/2609.22521)

## Abstract

The performance of learned robot visuomotor policies depends heavily on the size and quality of their training data, yet collecting high-quality demonstrations remains costly for robots in the real world. Although large-scale robot and human datasets are increasingly available, embodiment gaps and mismatched action spaces make them difficult to leverage directly. Cross-embodiment transfer, reusing experience from other embodiments to improve learning on a target embodiment, is therefore crucial for scaling robot learning beyond per-robot data collection. In this work, we find that efficient transfer can be achieved by learning from what is shared across embodiments, the visual dynamics of how the world responds to motion, and by effectively exploiting the scarce target-embodiment data at test time. The proposed framework, called Latent Policy Steering (LPS), implements an embodiment-agnostic pretraining phase, which trains an image-based World Model (WM) with optical flow across diverse embodiments. The resulting WM is finetuned on the target embodiment with robot actions. It then steers the base policy toward better actions by searching in the WM's latent space for plans that stay close to the finetuning data. LPS is a policy-agnostic framework: it can flexibly accommodate different policies without having to retrain them. In Robomimic and real-world evaluations, LPS improves the average performance of Diffusion Policy relatively by 16% and 62%, and Pi0.5 by 8% and 14%, with only 50 demonstrations on an unseen target embodiment.

## TL;DR

The performance of learned robot visuomotor policies depends heavily on the size and quality of their training data, yet collecting high-quality demonstrations remains costly for robots in the real world. Although large-scale robot and human datasets are increasingly available, embodiment gaps and mismatched action spaces make them difficult to leverage directly.

## Related
<!-- [[other-paper-citekey]] -->
