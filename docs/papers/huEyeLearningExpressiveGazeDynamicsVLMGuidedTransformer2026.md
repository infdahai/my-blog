---
citekey: "huEyeLearningExpressiveGazeDynamicsVLMGuidedTransformer2026"
title: "Eye, Robot: Learning Expressive Gaze Dynamics via a VLM-Guided Transformer-VAE"
authors: ["Yuhang Hu", "Junlin Lyu", "Yuan Fang", "Xiaoying Shen", "Lechen Zhang", "Jiong Lin", "Judah Goldfeder", "Steven Tian", "Hod Lipson"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.19635"
doi: "10.48550/arXiv.2610.19635"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-10-16
---

# Eye, Robot: Learning Expressive Gaze Dynamics via a VLM-Guided Transformer-VAE

> Yuhang Hu, Junlin Lyu, Yuan Fang, Xiaoying Shen, Lechen Zhang, Jiong Lin, Judah Goldfeder, Steven Tian, Hod Lipson · 2026
> [arXiv](https://arxiv.org/abs/2610.19635) · [PDF](https://arxiv.org/pdf/2610.19635)

## Abstract

Gaze coordinates attention in human interaction through coupled eye, head, and eyelid motion. A humanoid robot must choose where to look while generating a suitable movement toward that target; fixed tracking rules alone do not model the temporal structure of human gaze. We separate these tasks with an asynchronous vision-language model that selects a scene referent, a reactive perception module that maintains fixation, and a Realistic Gaze Transformer (RGT) that generates target-conditioned motion. RGT is a Transformer-VAE trained on markerless human recordings retargeted to the robot's 11-DoF joint space: self-supervised pretraining encodes recent full-head history, and autoregressive fine-tuning exposes the model to its own predictions during rollout. At inference, a four-dimensional binocular-eye trajectory conditions coordinated neck and eye motion; an auxiliary blink predictor triggers eyelid templates during playback. On a two-second benchmark in which all controllers receive the same ground-truth target, RGT-Base obtains the lowest reported overall seven-joint MSE, and physical demonstrations show the integrated targeting and control pipeline. The evidence establishes robot-space kinematic fidelity and real-time RGT inference; perceived naturalness and open-vocabulary target-selection accuracy remain questions for controlled evaluation.

## TL;DR

Gaze coordinates attention in human interaction through coupled eye, head, and eyelid motion. A humanoid robot must choose where to look while generating a suitable movement toward that target; fixed tracking rules alone do not model the temporal structure of human gaze.

## Related
<!-- [[other-paper-citekey]] -->
