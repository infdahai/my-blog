---
citekey: "zhouResidualModelingClosesRegressionGenerativePolicyGapLearning2026"
title: "Residual Modeling Closes the Regression and Generative Policy Gap in Robot Learning"
authors: ["Yuchen Zhou", "Jiacheng You", "Weikang Wan", "Weijun Dong", "Yang Gao", "Jiayuan Mao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.12231"
doi: "10.48550/arXiv.2610.12231"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-10
---

# Residual Modeling Closes the Regression and Generative Policy Gap in Robot Learning

> Yuchen Zhou, Jiacheng You, Weikang Wan, Weijun Dong, Yang Gao, Jiayuan Mao · 2026
> [arXiv](https://arxiv.org/abs/2610.12231) · [PDF](https://arxiv.org/pdf/2610.12231)

## Abstract

Learning from demonstration has enabled impressive robot behaviors. A common choice for policy learning is to use diffusion or flow matching (Flow-Policies), which often outperforms direct action regression trained with mean squared error (MSE-Policies). This gap is commonly attributed to multimodal demonstrations. We revisit this gap from the perspective of statistical modeling: how action-prediction residuals shape policy optimization. Our analysis of real-world robot demonstration data reveals substantial state-dependent variation in residual scales and heavier-than-Gaussian tails. While both MSE-Policies and Flow-Policies exhibit heavy-tailed action residuals, their training gradients behave differently: MSE allocates more gradient magnitude to observations with large action residuals, which hurts optimization. Motivated by these findings, we introduce heteroscedastic Student-t action regression (HT-Policies), which learns input-dependent residual scales and reduces the influence of heavy tails. HT-Policies predict action chunks with a single feed-forward pass and can reuse pretrained flow-matching-based policy networks as the backbone. Across four simulation benchmarks and real-robot evaluations, HT-Policies achieves success rates competitive with generative policy baselines, both when trained from scratch and from pretrained vision-language-action and world-action models, despite being faster in training and inference. Together, these findings shed light on the practical advantages of generative objectives in robot learning from demonstrations and offer an efficient direct-regression alternative for a range of architectures and tasks. Project page: https://the-labone.github.io/regression-policy-project/

## TL;DR

Learning from demonstration has enabled impressive robot behaviors. A common choice for policy learning is to use diffusion or flow matching (Flow-Policies), which often outperforms direct action regression trained with mean squared error (MSE-Policies).

## Related
<!-- [[other-paper-citekey]] -->
