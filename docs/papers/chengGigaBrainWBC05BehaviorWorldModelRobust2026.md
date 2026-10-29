---
citekey: "chengGigaBrainWBC05BehaviorWorldModelRobust2026"
title: "GigaBrain-WBC-0.5: A Behavior World Model for Robust Whole-Body Control with Environment Interaction"
authors: ["Ziyang Cheng", "Tianshu Tang", "Jinxin Lan", "Xinze Chen", "Yuhan Gong", "Zhichao Liu", "Changzhong Wu", "Yahao Mao", "Zongyan Deng", "Mingxuan Ma", "Huasen Xi", "Yilong Liu", "Yutong Wu", "Xiaofeng Wang", "Yang Wang", "Yun Ye", "Guan Huang", "Xiaojie Jin", "Zheng Zhu", "Jiwen Lu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.18234"
doi: "10.48550/arXiv.2608.18234"
tags: [paper, embodied-ai, "cs.AI", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-09-15
---

# GigaBrain-WBC-0.5: A Behavior World Model for Robust Whole-Body Control with Environment Interaction

> Ziyang Cheng, Tianshu Tang, Jinxin Lan, Xinze Chen, Yuhan Gong, Zhichao Liu, Changzhong Wu, Yahao Mao, Zongyan Deng, Mingxuan Ma, Huasen Xi, Yilong Liu, Yutong Wu, Xiaofeng Wang, Yang Wang, Yun Ye, Guan Huang, Xiaojie Jin, Zheng Zhu, Jiwen Lu · 2026
> [arXiv](https://arxiv.org/abs/2608.18234) · [PDF](https://arxiv.org/pdf/2608.18234)

## Abstract

Whole-body motion tracking policies turn a humanoid into a robust control interface: the teleoperator---or an upstream model---only supplies a coarse movement intent, while the low-level policy keeps the robot balanced and physically feasible. Existing trackers deliver this interface only on flat ground: trained in empty scenes, they never learn how contact with terrain and objects reshapes their dynamics, and they attempt to teach the policy to balance under any command by continually enlarging the reference-motion corpus, which stops working once feasible behaviors become environment-dependent. We present GigaBrain-WBC-0.5, the first Behavior World Model (BWM) for humanoid whole-body control. Rather than a purely reactive tracker, we train a causal Transformer to jointly predict its next action, next state, and the distribution over its next latent behavior command, so the network that acts also models how the environment shapes what it can do next. An automatic terrain-annotation pipeline recovers full 3D contact geometry from retargeted motion, enabling terrain annotation at the scale of existing motion datasets. The predicted distribution is reused at deployment to detect implausible commands online and retract them onto learned behaviors, so the robot attempts tasks in a "best-effort" manner. The result is a unified policy that takes real-time command, interacts with environment, and stays robust to implausible commands, falls, and disturbances. GigaBrain-WBC-0.5 achieves the highest success rate across all four regimes among three large-scale tracker baselines: 81.3% on terrain interaction (4.3x the strongest baseline), 83.1% under implausible commands, and 99.3% fall recovery (16.8x the strongest baseline). Hardware trials show robust interaction under missing supports and disturbances; the Unitree G1 checkpoint transfers to the Maker L01 robot with simple fine-tuning.

## TL;DR

Whole-body motion tracking policies turn a humanoid into a robust control interface: the teleoperator---or an upstream model---only supplies a coarse movement intent, while the low-level policy keeps the robot balanced and physically feasible. Existing trackers deliver this interface only on flat ground: trained in empty scenes, they never learn how contact with terrain and objects reshapes their dynamics, and they attempt to teach the policy to balance under any command by continually enlarging the reference-motion corpus, which stops working once feasible behaviors become...

## Related
<!-- [[other-paper-citekey]] -->
