---
citekey: "zhouThinkOnlyWhenNeededPromptAuthorityControlSelective2026"
title: "Think Only When Needed: Prompt-Authority Control for Selective Slow-Path Intervention in Vision-Language-Action Manipulation"
authors: ["Zhiruo Zhou", "Zelin Li", "Xiwen Chen", "Jiazhuo Li", "Chenwei Wang", "Huiming Chen", "Xiaojun Zhu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.23224"
doi: "10.48550/arXiv.2608.23224"
tags: [paper, embodied-ai, "cs.AI", "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-08-26
---

# Think Only When Needed: Prompt-Authority Control for Selective Slow-Path Intervention in Vision-Language-Action Manipulation

> Zhiruo Zhou, Zelin Li, Xiwen Chen, Jiazhuo Li, Chenwei Wang, Huiming Chen, Xiaojun Zhu · 2026
> [arXiv](https://arxiv.org/abs/2608.23224) · [PDF](https://arxiv.org/pdf/2608.23224)

## Abstract

Retrieval can efficiently and effectively augment a frozen vision--language--action (VLA) policy without retraining, yet retrieved text becomes a control intervention once it enters the executed prompt. In a matched audit, raw appended text reduces mean success from 92.47\% to 3.00\%, while meaningful and length-matched meaningless appends both fail on all 500 states. This result identifies \emph{prompt-form collapse}: changing the instruction form, rather than adding useful semantics, can dominate execution. We introduce TOWN-VLA (Think Only When Needed), a prompt-authority interface that separates candidate generation from permission to alter the policy input. A fixed compatibility rule authorizes a canonical compact instruction; otherwise, the interface restores the original Base prompt exactly. Across 900 audited routes, every route follows this contract: 525 routes recover Base with matching hashes, and all 375 authorized prompts preserve the task signature. On a matched $4\times7$ LIBERO-Plus evaluation with 10{,}030 episodes per method, success rises from 69.5\% to 73.1\% ($+362$ episodes; 95\% CI 1.89--5.45 points), improving on six perturbation axes and all four suites. On a physical PiPER arm with a frozen \pizerofive{} checkpoint, success rises from 52.7\% to 78.7\% over 150 trials per method ($p=3.16\times10^{-6}$). Prompt authority is enforceable for a frozen controller; oracle-free admission calibration is the next deployment target.

## TL;DR

Retrieval can efficiently and effectively augment a frozen vision--language--action (VLA) policy without retraining, yet retrieved text becomes a control intervention once it enters the executed prompt. In a matched audit, raw appended text reduces mean success from 92.47\% to 3.00\%, while meaningful and length-matched meaningless appends both fail on all 500 states.

## Related
<!-- [[other-paper-citekey]] -->
