---
citekey: "liuConfALWMConfidenceGuidedActiveLearningActionConditioned2026"
title: "ConfAL-WM: Confidence-Guided Active Learning for Action-Conditioned World Models"
authors: ["Xiang Liu", "Sen Cui", "Changshui Zhang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.25572"
doi: "10.48550/arXiv.2608.25572"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# ConfAL-WM: Confidence-Guided Active Learning for Action-Conditioned World Models

> Xiang Liu, Sen Cui, Changshui Zhang · 2026
> [arXiv](https://arxiv.org/abs/2608.25572) · [PDF](https://arxiv.org/pdf/2608.25572)

## Abstract

Action-conditioned world models have become an important foundation for embodied prediction, planning, and synthetic data generation, but their errors under new task and scene distributions are often concentrated in localized spatiotemporal regions such as robot arms, manipulated objects, contact areas, and occluded objects. This paper presents ConfAL-WM, a confidence-guided active learning framework for post-training embodied world models. Built upon EVAC, we attach a lightweight confidence probe to UNet decoder features and predict dense confidence maps in the latent space. These maps are aggregated into task-, frame-, and patch-level scores, enabling both efficient data selection and localized training enhancement. Our pipeline first retrains the confidence probe and warms up EVAC with a small subset of target-domain data, then performs task-level prescreening to allocate sampling budgets, and finally applies selected-data retraining with optional frame or patch weighted data enhancement. Experiments on RoboTwin2.0 show that confidence-guided selection improves post-training efficiency, while dense frame and patch weighting further enhances prediction quality and embodied trajectory consistency compared with scalar reward, progress, and judge-based scoring baselines. A quick visual overview of this work is available at https://ConfAL-WM.github.io.

## TL;DR

Action-conditioned world models have become an important foundation for embodied prediction, planning, and synthetic data generation, but their errors under new task and scene distributions are often concentrated in localized spatiotemporal regions such as robot arms, manipulated objects, contact areas, and occluded objects. This paper presents ConfAL-WM, a confidence-guided active learning framework for post-training embodied world models.

## Related
<!-- [[other-paper-citekey]] -->
