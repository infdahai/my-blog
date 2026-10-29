---
citekey: "gaoHowMuchCanBestNHelpWorldAction2026"
title: "How Much Can Best-of-N Help a World Action Model? Measuring Selectable Headroom and Realizing It in Closed Loop"
authors: ["Haojia Gao", "Yue Cao", "Yumin Liu", "Haohua Que", "Mingkai Liu", "Guanqiu Guo", "Zhuo Zou", "Bokui Chen", "Xueqian Wang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.37196"
doi: "10.48550/arXiv.2610.37196"
tags: [paper, embodied-ai, "cs.CV", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-29
---

# How Much Can Best-of-N Help a World Action Model? Measuring Selectable Headroom and Realizing It in Closed Loop

> Haojia Gao, Yue Cao, Yumin Liu, Haohua Que, Mingkai Liu, Guanqiu Guo, Zhuo Zou, Bokui Chen, Xueqian Wang · 2026
> [arXiv](https://arxiv.org/abs/2610.37196) · [PDF](https://arxiv.org/pdf/2610.37196)

## Abstract

World action models (WAMs) predict the visual consequences of the actions they generate, which makes test-time selection a natural way to improve a fixed policy: imagine the futures of candidate actions and execute the best one. The benefit of selection is bounded by the selectable headroom, how much better the best candidate truly is, but the standard estimate, which executes each candidate once and keeps the best outcome, conflates candidate quality with the randomness of everything that follows. We introduce a denoised counterfactual protocol, based on bitwise-reproducible branching, repeated continuations, held-out oracles, and common random numbers, that measures the headroom a selector can realize, and use its measurements to build a fail-gated selector. Across four WAMs, two benchmarks, over 100,000 branched rollouts, and pre-registered tests, we find that (i) the standard estimate overstates the selectable headroom of native samples: bounds from 17 continuations per candidate place its selectable share between 24% and 66% for three WAMs; (ii) structured action perturbations create up to 16 points of selectable headroom; and (iii) in both WAMs with action-conditioned imagination, imagined futures carry candidate-outcome information with no detectable loss relative to real futures, information that the value head of Cosmos Policy leaves unused. Deviating from the policy chunk only when a readout of the WAM predicts failure, the selector raises closed-loop task success from 76.9% to 81.6% on held-out episodes of training tasks, with the largest gain where the policy fails most often, and from 62.6% to 69.8% on unseen tasks.

## TL;DR

World action models (WAMs) predict the visual consequences of the actions they generate, which makes test-time selection a natural way to improve a fixed policy: imagine the futures of candidate actions and execute the best one. The benefit of selection is bounded by the selectable headroom, how much better the best candidate truly is, but the standard estimate, which executes each candidate once and keeps the best outcome, conflates candidate quality with the randomness of everything that follows.

## Related
<!-- [[other-paper-citekey]] -->
