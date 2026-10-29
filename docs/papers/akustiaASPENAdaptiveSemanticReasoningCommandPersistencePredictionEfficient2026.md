---
citekey: "akustiaASPENAdaptiveSemanticReasoningCommandPersistencePredictionEfficient2026"
title: "ASPEN: Adaptive Semantic Reasoning via Command Persistence Prediction for Efficient Navigation VLAs"
authors: ["Vieri N. Akustia", "Bin Hu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.36285"
doi: "10.48550/arXiv.2610.36285"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-29
---

# ASPEN: Adaptive Semantic Reasoning via Command Persistence Prediction for Efficient Navigation VLAs

> Vieri N. Akustia, Bin Hu · 2026
> [arXiv](https://arxiv.org/abs/2610.36285) · [PDF](https://arxiv.org/pdf/2610.36285)

## Abstract

Navigation vision-language-action (VLA) policies repeatedly invoke costly semantic reasoning even when the next command remains unchanged. Command reuse can reduce computation but risks missing instruction-dependent turns or stops. We introduce ASPEN, an event-triggered scheduler based on command persistence prediction: estimating whether the frozen base policy would reissue its previous command. A lightweight multimodal predictor combines temporal observations, language instructions, execution history, and cached VLA confidence. At eligible command boundaries, sufficient predicted persistence permits command reuse. Otherwise, ASPEN triggers fresh semantic reasoning from the VLA. Evaluated with frozen NaVILA on cross-dataset RxR-CE val-unseen, ASPEN reduces VLA calls by 9.5% and estimated inference time by 8.1%, including scheduling overhead. It maintains comparable navigation performance and preserves identical baseline action sequences on 92.1% of episodes.

## TL;DR

Navigation vision-language-action (VLA) policies repeatedly invoke costly semantic reasoning even when the next command remains unchanged. Command reuse can reduce computation but risks missing instruction-dependent turns or stops.

## Related
<!-- [[other-paper-citekey]] -->
