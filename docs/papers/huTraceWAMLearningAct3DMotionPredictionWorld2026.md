---
citekey: "huTraceWAMLearningAct3DMotionPredictionWorld2026"
title: "Trace-WAM: Learning to Act via 3D Motion Prediction for World Action Models"
authors: ["Xu Hu", "Changjie Wu", "Linzhe Shi", "Hang Zhang", "Chen Yang", "Lingjun Zhang", "Guowen Zhang", "Mu Xu", "Junran Peng", "Qing Li", "Zhaoxiang Zhang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.36840"
doi: "10.48550/arXiv.2610.36840"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-29
---

# Trace-WAM: Learning to Act via 3D Motion Prediction for World Action Models

> Xu Hu, Changjie Wu, Linzhe Shi, Hang Zhang, Chen Yang, Lingjun Zhang, Guowen Zhang, Mu Xu, Junran Peng, Qing Li, Zhaoxiang Zhang · 2026
> [arXiv](https://arxiv.org/abs/2610.36840) · [PDF](https://arxiv.org/pdf/2610.36840)

## Abstract

World Action Models (WAMs) learn representations for robot control by coupling future visual prediction with action generation. Successful manipulation depends primarily on how the robot and task-relevant objects evolve, whereas future-video prediction must also reconstruct the appearance and background of the entire scene. We therefore propose Trace-WAM, which augments video-action learning with future 3D motion prediction as an auxiliary objective. This objective supervises temporal point correspondence together with image-plane displacement and depth change, directly describing the interaction dynamics and spatial changes involved in manipulation. To this end, we adopt a three-branch Mixture-of-Transformer (Tri-MoT) architecture to jointly learn video prediction, motion prediction, and action generation. The motion expert predicts future trajectories from current visual features, allowing motion supervision to shape the representations used for action generation. Because the action expert does not consume predicted trajectories, inference retains the current-observation policy path: a single visual forward pass followed by action denoising. Experiments on RoboCasa-GR1, LIBERO, and LIBERO-Plus demonstrate strong in-distribution performance and out-of-distribution generalization, with particularly clear gains over Fast-WAM under limited demonstrations and distribution shifts.

## TL;DR

World Action Models (WAMs) learn representations for robot control by coupling future visual prediction with action generation. Successful manipulation depends primarily on how the robot and task-relevant objects evolve, whereas future-video prediction must also reconstruct the appearance and background of the entire scene.

## Related
<!-- [[other-paper-citekey]] -->
