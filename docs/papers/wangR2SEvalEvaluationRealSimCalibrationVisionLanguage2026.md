---
citekey: "wangR2SEvalEvaluationRealSimCalibrationVisionLanguage2026"
title: "R2S-Eval: Robot Evaluation with Real-to-Sim Calibration via Vision-Language Models"
authors: ["Yidi Wang", "Feixiang Ruan", "Ruoqu Chen", "Jie Yin", "Yang Yu", "Mengdi Xu", "Kaifeng Zhang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.03276"
doi: "10.48550/arXiv.2609.03276"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-07
---

# R2S-Eval: Robot Evaluation with Real-to-Sim Calibration via Vision-Language Models

> Yidi Wang, Feixiang Ruan, Ruoqu Chen, Jie Yin, Yang Yu, Mengdi Xu, Kaifeng Zhang · 2026
> [arXiv](https://arxiv.org/abs/2609.03276) · [PDF](https://arxiv.org/pdf/2609.03276)

## Abstract

Evaluating robot manipulation policies is becoming increasingly important as generalist models, particularly vision-language-action (VLA) models, are deployed on physical robots. However, conventional real-world evaluation remains labor-intensive, unstable, and insufficiently informative. It requires repeated hardware trials, manual scene resets, and continuous operator monitoring, may produce different policy rankings across repeated evaluations, and primarily relies on success-rate metrics that provide limited information about execution quality. In contrast, humans assess robot performance by observing and comparing complete behaviors rather than relying solely on binary success outcomes. To this end, we propose R2S-Eval, an evaluation pipeline that combines real-to-sim calibration with vision-language model (VLM) preference evaluation. The real-to-sim component efficiently generates rollout videos in a simulator calibrated to the real-world evaluation setting, thereby reducing the need for repeated hardware trials. The VLM evaluator assesses the execution quality of rollout videos and produces pairwise preferences, which are subsequently aggregated into policy rankings. We further introduce a protocol to assess whether the proposed evaluation pipeline yields validated policy conclusions while mitigating the key challenges of conventional real-world evaluation. Experiments in both simulation and real-world settings demonstrate that R2S-Eval produces reliable and stable policy conclusions, achieves agreement with human preferences, substantially reduces repeated hardware-operation effort, and reveals behavior-quality differences that are not captured by binary success labels. In general, R2S-Eval advances robot evaluation from manual success counting toward automated, statistically stable, and quality-aware evaluation of robot behavior. Project page: https://r2s-eval.github.io.

## TL;DR

Evaluating robot manipulation policies is becoming increasingly important as generalist models, particularly vision-language-action (VLA) models, are deployed on physical robots. However, conventional real-world evaluation remains labor-intensive, unstable, and insufficiently informative.

## Related
<!-- [[other-paper-citekey]] -->
