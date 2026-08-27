---
citekey: "chengRobustBimanualVisionLanguageActionModelsEmbarrassinglySimple2026"
title: "Robust Bimanual Vision-Language-Action Models via Embarrassingly Simple Modality Masking"
authors: ["Dongzhou Cheng", "Ziang Li", "Yixiao Zhou", "Haojuan Li", "Jinghao Zhang", "Lei Lei", "Minjing Dong", "Jie Gui", "Jiaqi Wang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.22419"
doi: "10.48550/arXiv.2608.22419"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# Robust Bimanual Vision-Language-Action Models via Embarrassingly Simple Modality Masking

> Dongzhou Cheng, Ziang Li, Yixiao Zhou, Haojuan Li, Jinghao Zhang, Lei Lei, Minjing Dong, Jie Gui, Jiaqi Wang · 2026
> [arXiv](https://arxiv.org/abs/2608.22419) · [PDF](https://arxiv.org/pdf/2608.22419)

## Abstract

Query-based Vision-Language-Action (VLA) models offer low-latency inference that is attractive for bimanual robotic manipulation, but we observe that they can still exhibit discontinuous actions and execution failures in complex dual-arm tasks. We hypothesize that unstable multi-view and language fusion is one contributing factor in these failures, often coinciding with attention spreading to distracting regions. To improve robustness, we introduce the Modality Masking Mechanism (M3), an embarrassingly simple, training-only strategy that requires no architectural changes or large-scale robot pretraining. M3 stochastically masks subsets of modality channels during training, exposing the policy to controlled partial observations and encouraging it to rely less on distracting cues and more on evidence that remains reliable. We evaluate M3 on ten bimanual tasks from RoboTwin 2.0 and on three long-horizon real-world tasks. Compared with the Adapter baseline, M3 improves average success by 21.7% in the Clean setting and 11.4% in Clean2Rand, where policies are trained on clean demonstrations and evaluated on randomized scenes, while also improving averaged real-world full-task success by over 30%. These results suggest that structured training-time masking is a practical way to improve the robustness of query-based VLA policies for bimanual manipulation.

## TL;DR

Query-based Vision-Language-Action (VLA) models offer low-latency inference that is attractive for bimanual robotic manipulation, but we observe that they can still exhibit discontinuous actions and execution failures in complex dual-arm tasks. We hypothesize that unstable multi-view and language fusion is one contributing factor in these failures, often coinciding with attention spreading to distracting regions.

## Related
<!-- [[other-paper-citekey]] -->
