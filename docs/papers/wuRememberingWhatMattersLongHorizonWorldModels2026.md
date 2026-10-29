---
citekey: "wuRememberingWhatMattersLongHorizonWorldModels2026"
title: "Remembering What Matters for Long-Horizon Robotic World Models"
authors: ["Hao Wu", "Tianyu Shao", "Shengju Qian", "Yizhou Zhao", "Fan Zhang", "Penghao Zhao", "Weiyan Wang", "Yufei Huang", "Fan Xu", "Kun Wang", "Xin Wang", "Ming-Hsuan Yang", "Yuxuan Liang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.14583"
doi: "10.48550/arXiv.2610.14583"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-15
---

# Remembering What Matters for Long-Horizon Robotic World Models

> Hao Wu, Tianyu Shao, Shengju Qian, Yizhou Zhao, Fan Zhang, Penghao Zhao, Weiyan Wang, Yufei Huang, Fan Xu, Kun Wang, Xin Wang, Ming-Hsuan Yang, Yuxuan Liang · 2026
> [arXiv](https://arxiv.org/abs/2610.14583) · [PDF](https://arxiv.org/pdf/2610.14583)

## Abstract

Autoregressive robot video world models based on discrete visual tokens remain unreliable over long rollout horizons. Retaining the entire generated history does not necessarily improve prediction quality. We investigate a possible memory-role conflict in Full Context decoding: persistent scene information, recent visual-action states, and stale generated history compete for attention despite their different predictive roles. This perspective motivates ReCAP (Receding Context with Anchor Preservation), a training-free context-scheduling method for long-horizon robot video world models. ReCAP keeps the pretrained tokenizer, world model, and visual decoder frozen. It preserves the initial scene anchor and a contiguous window of recent complete visual-action blocks while evicting older generated history. The schedule preserves within-block structure and temporal order, requires no additional modules or parameter updates, and bounds active-context growth independently of rollout length. We evaluate ReCAP on RT-1, BridgeV2, LIBERO-90, and CALVIN using frozen autoregressive world models. Across evaluated environments and horizons, ReCAP improves visual fidelity, action-conditioned consistency, and robot structure preservation relative to Full Context. On BridgeV2, it reduces LPIPS by 63.3%. In the system benchmark at H=64, it reduces the logical KV footprint by 73.3% and p50 latency by 6.51%. Attention analyses show increased attention to retained recent states, while history interventions associate larger amounts of stale context with higher prediction error. These observations are consistent with the memory-role-conflict hypothesis, although they do not isolate it from context-length and position-handling effects. Our results support inference-time context scheduling as a practical approach to improving long-horizon robot video prediction and computational efficiency without retraining.

## TL;DR

Autoregressive robot video world models based on discrete visual tokens remain unreliable over long rollout horizons. Retaining the entire generated history does not necessarily improve prediction quality.

## Related
<!-- [[other-paper-citekey]] -->
