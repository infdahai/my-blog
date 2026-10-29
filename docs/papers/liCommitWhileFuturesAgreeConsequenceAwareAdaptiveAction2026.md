---
citekey: "liCommitWhileFuturesAgreeConsequenceAwareAdaptiveAction2026"
title: "Commit While Futures Agree: Consequence-Aware Adaptive Action Chunking for Robot Manipulation"
authors: ["Yuyan Li", "Yujia Wang", "Yusong Huang", "Junjie Yang", "Yanggang Sheng", "Ziyi Shi", "Wenpeng Xu", "Xiaoyang Zhou", "Haoang Li", "Hongliang Lu", "Xinhu Zheng"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.07949"
doi: "10.48550/arXiv.2610.07949"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-08
---

# Commit While Futures Agree: Consequence-Aware Adaptive Action Chunking for Robot Manipulation

> Yuyan Li, Yujia Wang, Yusong Huang, Junjie Yang, Yanggang Sheng, Ziyi Shi, Wenpeng Xu, Xiaoyang Zhou, Haoang Li, Hongliang Lu, Xinhu Zheng · 2026
> [arXiv](https://arxiv.org/abs/2610.07949) · [PDF](https://arxiv.org/pdf/2610.07949)

## Abstract

Action-chunking policies predict multi-step control sequences, but a fundamental question remains: how much of a predicted action chunk should be committed before replanning? Existing systems typically execute a fixed-length prefix, implicitly assuming that the same execution horizon remains trustworthy across states. Some adaptive methods estimate this horizon from the similarity or stability of predicted actions. However, different actions may lead to the same successful outcome, whereas similar actions can produce different futures, suggesting that commitment should be determined by agreement among imagined futures rather than by similarity in action space. To this end, we propose Consequence-Aware Adaptive Action Chunking (CA$^3$C), an inference-time framework built on a simple principle: commit while imagined futures agree, and replan when they diverge. Without modifying or retraining the base policy, CA$^3$C uses an action-conditioned world model to imagine the future consequences of multiple candidate action chunks under the same sampling noise. Using these imagined consequences, we formulate execution-horizon estimation as a Bayesian change-point inference problem and select the execution candidate through future consensus. Across multiple simulation benchmarks and real-world robot manipulation tasks, CA$^3$C consistently improves diverse action-chunking policies, achieving up to a 71.8% relative reduction in failure rate over the corresponding base policies.

## TL;DR

Action-chunking policies predict multi-step control sequences, but a fundamental question remains: how much of a predicted action chunk should be committed before replanning? Existing systems typically execute a fixed-length prefix, implicitly assuming that the same execution horizon remains trustworthy across states.

## Related
<!-- [[other-paper-citekey]] -->
