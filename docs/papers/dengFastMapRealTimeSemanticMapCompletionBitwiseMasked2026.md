---
citekey: "dengFastMapRealTimeSemanticMapCompletionBitwiseMasked2026"
title: "FastMap: Real-Time Semantic Map Completion via Bitwise Masked Modeling"
authors: ["Yijie Deng", "Shuaihang Yuan", "Congcong Wen", "Hao Huang", "Anthony Tzes"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2506.07350"
doi: "10.48550/arXiv.2506.07350"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-12
---

# FastMap: Real-Time Semantic Map Completion via Bitwise Masked Modeling

> Yijie Deng, Shuaihang Yuan, Congcong Wen, Hao Huang, Anthony Tzes · 2026
> [arXiv](https://arxiv.org/abs/2506.07350) · [PDF](https://arxiv.org/pdf/2506.07350)

## Abstract

Semantic map completion, which predicts the layout of unobserved regions from partial observations, is a critical capability for indoor robot navigation. Existing approaches either rely on high-dimensional discrete codebooks that inflate memory, or on iterative diffusion sampling that is too slow for real-time use. We present FastMap, a lightweight two-stage framework for completing top-down categorical semantic maps. First, a lookup-free BitVAE exploits the inherently binary (one-hot) structure of semantic maps to compress each map patch into compact bitwise tokens, yielding a 0.41GB model that is 3.7 times smaller than the prior masked-modeling baseline. Second, a Masked AutoEncoder (MAE)-style transformer reconstructs missing tokens in a single forward pass at 0.011s/map. To support object goal navigation, we additionally introduce an object-aware masking strategy that masks the target category during training and conditions generation on a learnable category embedding, without adding inference cost. On the Gibson benchmark, FastMap achieves 34.10% mIoU and 45.84% semantic Success Rate (sSR), more than doubling the previous best (21.88%), and reaches 83.8% Success Rate on downstream ObjectNav, the highest among the compared navigation methods.

## TL;DR

Semantic map completion, which predicts the layout of unobserved regions from partial observations, is a critical capability for indoor robot navigation. Existing approaches either rely on high-dimensional discrete codebooks that inflate memory, or on iterative diffusion sampling that is too slow for real-time use.

## Related
<!-- [[other-paper-citekey]] -->
