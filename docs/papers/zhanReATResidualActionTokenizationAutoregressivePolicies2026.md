---
citekey: "zhanReATResidualActionTokenizationAutoregressivePolicies2026"
title: "ReAT: Residual Action Tokenization for Autoregressive Robot Policies"
authors: ["Dijia Zhan", "Zhuo Li", "Xuemiao Xu", "Sun Zheng", "Jinyi Li", "Wenjun Wang", "Jie Tang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.13093"
doi: "10.48550/arXiv.2610.13093"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-13
---

# ReAT: Residual Action Tokenization for Autoregressive Robot Policies

> Dijia Zhan, Zhuo Li, Xuemiao Xu, Sun Zheng, Jinyi Li, Wenjun Wang, Jie Tang · 2026
> [arXiv](https://arxiv.org/abs/2610.13093) · [PDF](https://arxiv.org/pdf/2610.13093)

## Abstract

Autoregressive robot policies rely on action tokenizers to convert continuous action chunks into compact sequences of discrete prediction targets. Existing tokenizers can reconstruct action chunks from discrete codes, but often leave implicit what each individual token contributes to the reconstructed action. We introduce Residual Action Tokenization (ReAT), which gives each token an explicit role in refining the current action reconstruction. It uses the decoded reconstruction as feedback to construct the next token from the remaining action error. This closes the loop between encoding and decoding, making each new token responsive to the errors left by the actual decoded prefix. Across 19 manipulation tasks spanning three simulation benchmarks and real-world settings, 8-token ReAT policies outperform the evaluated baselines in task success; on LIBERO, even 4-token ReAT surpasses the evaluated 8-token action-tokenization baselines at half the token budget. These results suggest a path toward action tokenization that supports self-corrective policy learning, helping autoregressive policies learn to progressively refine their own action plans.

## TL;DR

Autoregressive robot policies rely on action tokenizers to convert continuous action chunks into compact sequences of discrete prediction targets. Existing tokenizers can reconstruct action chunks from discrete codes, but often leave implicit what each individual token contributes to the reconstructed action.

## Related
<!-- [[other-paper-citekey]] -->
