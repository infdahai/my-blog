---
citekey: "fuTokenWorldWorldModelingVisionLanguageModelToken2026"
title: "Token-World: World Modeling in Vision-Language Model Token Space for Robot Manipulation"
authors: ["Chuyao Fu", "Xiaowei Chi", "Yuhan Rui", "Yu-kai Wang", "Zezhong Qian", "Xiaojie Zhang", "Yunfan Lou", "Kevin Zhang", "Kuangzhi Ge", "Chak Wing Mak", "Zhiyang Chen", "Athena Zhuoming Zhong", "Hongyang Chen", "Haoran Li", "Yike Guo", "Sirui Han", "Shanghang Zhang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.00575"
doi: "10.48550/arXiv.2610.00575"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# Token-World: World Modeling in Vision-Language Model Token Space for Robot Manipulation

> Chuyao Fu, Xiaowei Chi, Yuhan Rui, Yu-kai Wang, Zezhong Qian, Xiaojie Zhang, Yunfan Lou, Kevin Zhang, Kuangzhi Ge, Chak Wing Mak, Zhiyang Chen, Athena Zhuoming Zhong, Hongyang Chen, Haoran Li, Yike Guo, Sirui Han, Shanghang Zhang · 2026
> [arXiv](https://arxiv.org/abs/2610.00575) · [PDF](https://arxiv.org/pdf/2610.00575)

## Abstract

A common approach to world-model simulation for vision-language-action (VLA) systems is to predict future RGB observations and then re-encode them into policy inputs, introducing an indirect interface between simulation and downstream policy execution. We instead investigate whether world dynamics can be modeled in a compact, policy-oriented state derived from VLM visual tokens. A key challenge is that raw VLM visual tokens are high-dimensional, making efficient and accurate autoregressive dynamics modeling challenging. To address this, we introduce Token-World, an action-conditioned world model that compresses VLM features into a compact token state, learns future dynamics in this reduced space, and maps predicted states back to the original policy-facing representation for downstream use. Across manipulation benchmarks, Token-World improves open-loop feature fidelity and policy-action consistency over recent world-model simulators, with slower degradation over long rollout horizons. In closed-loop evaluation, its simulated policy performance correlates more strongly with reference policy performance than Ctrl-World ($r=0.794$ vs.\ $0.583$), while requiring lower simulation latency. Ablations further show that compact-representation design and dimensionality substantially affect future-state prediction. Code will be available at https://chuyaofu.github.io/Token-World/.

## TL;DR

A common approach to world-model simulation for vision-language-action (VLA) systems is to predict future RGB observations and then re-encode them into policy inputs, introducing an indirect interface between simulation and downstream policy execution. We instead investigate whether world dynamics can be modeled in a compact, policy-oriented state derived from VLM visual tokens.

## Related
<!-- [[other-paper-citekey]] -->
