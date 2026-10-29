---
citekey: "liuGAWMCompactLatentWorldActionModelMultiTask2026"
title: "GAWM: A Compact Latent World-Action Model for Multi-Task Robot Manipulation"
authors: ["Yang Liu", "Xiaoli Liu", "Liuzhao Li", "Yuduo Song", "Muyuan Liu", "Xiang Gao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.37091"
doi: "10.48550/arXiv.2610.37091"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-29
---

# GAWM: A Compact Latent World-Action Model for Multi-Task Robot Manipulation

> Yang Liu, Xiaoli Liu, Liuzhao Li, Yuduo Song, Muyuan Liu, Xiang Gao · 2026
> [arXiv](https://arxiv.org/abs/2610.37091) · [PDF](https://arxiv.org/pdf/2610.37091)

## Abstract

World-action models (WAMs) incorporate the prediction of future observations into robot policy learning. However, most WAMs build on billion-parameter vision-language or video-generation backbones, which incur high training cost and inference latency. In this letter, we present GAWM (Geometry-Aware World Model), a compact multi-task WAM that predicts future observations in the latent space of a frozen DINOv3 encoder. GAWM compresses the features of each camera view into a small set of tokens. A lightweight predictor, conditioned on the task rather than on actions, forecasts these tokens at two future horizons. The forecast is supervised with the dense patch features of future frames, which requires it to encode the spatial layout of the future scene. An action decoder directly regresses a chunk of future actions from the current and predicted tokens. With fewer than 100M parameters and no robot or video pretraining, GAWM outperforms billion-parameter WAMs on RoboTwin 2.0 and performs comparably to billion-parameter VLAs on LIBERO. On a dual-arm robot, it achieves lower action-prediction error on held-out demonstrations than a fine-tuned billion-parameter VLA, with substantially lower inference latency. Ablation studies show that the latent world model substantially improves performance when training data or training time is limited. Code is available at https://github.com/gaoxiang12/ga-wm.

## TL;DR

World-action models (WAMs) incorporate the prediction of future observations into robot policy learning. However, most WAMs build on billion-parameter vision-language or video-generation backbones, which incur high training cost and inference latency.

## Related
<!-- [[other-paper-citekey]] -->
