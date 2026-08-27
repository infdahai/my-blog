---
citekey: "zhouSurgSyncTimeSynchronizedMultiModalDataCollectionFramework2026"
title: "SurgSync: Time-Synchronized Multi-Modal Data Collection Framework and Dataset for Surgical Robotics"
authors: ["Haoying Zhou", "Chang Liu", "Yimeng Wu", "Junlin Wu", "Zijian Wu", "Yu Chung Lee", "Sara Martuscelli", "Spetimiu E. Salcudean", "Gregory S. Fischer", "Peter Kazanzides"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2603.06919"
doi: "10.48550/arXiv.2603.06919"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# SurgSync: Time-Synchronized Multi-Modal Data Collection Framework and Dataset for Surgical Robotics

> Haoying Zhou, Chang Liu, Yimeng Wu, Junlin Wu, Zijian Wu, Yu Chung Lee, Sara Martuscelli, Spetimiu E. Salcudean, Gregory S. Fischer, Peter Kazanzides · 2026
> [arXiv](https://arxiv.org/abs/2603.06919) · [PDF](https://arxiv.org/pdf/2603.06919)

## Abstract

Most existing robotic surgery systems adopt a human-in-the-loop paradigm, often with the surgeon directly teleoperating the robotic system. Adding intelligence to these robots would enable higher-level control, such as supervised autonomy or even full autonomy. However, artificial intelligence (AI) requires large amounts of training data, which is currently lacking. This work proposes SurgSync, a multi-modal data collection framework with offline and online synchronization to support training and real-time inference, respectively. The framework is implemented on a da Vinci Research Kit (dVRK) and introduces (1) dual-mode (online/offline-matching) synchronized recorders, (2) a modern stereo endoscope to achieve image quality on par with clinical systems, and (3) additional sensors such as a side-view camera and a novel capacitive contact sensor to provide ground truth contact data. The framework also incorporates a post-processing toolbox for tasks such as depth estimation, optical flow, and a practical kinematic reprojection method using Gaussian heatmap. User studies with participants of varying skill levels are performed with ex-vivo tissue to provide clinically realistic data, and a network for surgical skill assessment is employed to demonstrate utilization of the collected data. Through the user study experiments, we obtained a dataset of 214 validated instances across multiple canonical training tasks. All software and data are available at surgsync.github.io.

## TL;DR

Most existing robotic surgery systems adopt a human-in-the-loop paradigm, often with the surgeon directly teleoperating the robotic system. Adding intelligence to these robots would enable higher-level control, such as supervised autonomy or even full autonomy.

## Related
<!-- [[other-paper-citekey]] -->
