---
citekey: "shiraiTOASTStochasticActionTokenizationAutoregressiveVisionLanguageAction2026"
title: "TOAST: Stochastic Robot Action Tokenization for Autoregressive Vision-Language-Action Models"
authors: ["Keisuke Shirai", "Tomohiro Motoda", "Hanbit Oh", "Ryoichi Nakajo", "Roman Mykhailyshyn", "Ryo Hanai", "Shotaro Miwa", "Yukiyasu Domae"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.00899"
doi: "10.48550/arXiv.2610.00899"
tags: [paper, embodied-ai, "cs.AI", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# TOAST: Stochastic Robot Action Tokenization for Autoregressive Vision-Language-Action Models

> Keisuke Shirai, Tomohiro Motoda, Hanbit Oh, Ryoichi Nakajo, Roman Mykhailyshyn, Ryo Hanai, Shotaro Miwa, Yukiyasu Domae · 2026
> [arXiv](https://arxiv.org/abs/2610.00899) · [PDF](https://arxiv.org/pdf/2610.00899)

## Abstract

Autoregressive Vision-Language-Action models often represent continuous robot actions as discrete token sequences, enabling action prediction with standard next-token objectives. FAST has substantially improved this representation by compactly encoding action containing diverse temporal frequencies into relatively few tokens. However, while such compression reduces the number of action tokens required for autoregressive prediction, it does not necessarily improve the efficiency of policy learning from limited demonstrations. In particular, FAST typically assigns a single deterministic tokenization to each quantized action sequence, although multiple token sequences can represent and decode to the same robot motion. We investigate whether exploiting this representational redundancy can improve policy learning. In this paper, we propose TOkenization of Action sequences with STochastic sampling (TOAST), a stochastic action tokenization method that samples alternative tokenizations of the same quantized action sequence during policy training. This diversifies the discrete supervision while preserving the underlying robot action and requires no additional demonstrations. Experiments on LIBERO show that TOAST consistently improves over its deterministic counterpart, with the improvement increasing as training data decreases, achieving a 6.8 point gain in success rate when only 1/16 of training data is available. Across four real-robot manipulation tasks, TOAST further improves mean success rate by 15.8 points over the deterministic counterpart. These results demonstrate the effectiveness of stochastic action tokenization for autoregressive robot policy learning, particularly when training data are limited.

## TL;DR

Autoregressive Vision-Language-Action models often represent continuous robot actions as discrete token sequences, enabling action prediction with standard next-token objectives. FAST has substantially improved this representation by compactly encoding action containing diverse temporal frequencies into relatively few tokens.

## Related
<!-- [[other-paper-citekey]] -->
