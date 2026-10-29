---
citekey: "huangProfessionalTennisStylesHumanoidAdaptiveMotionPlanningTracking2026"
title: "Towards Professional Tennis Styles for Humanoid Robots with Adaptive Motion Planning and Tracking"
authors: ["Tao Huang", "Ruofei Liu", "Xuchen Tang", "Xinyin Zhang", "Junli Ren", "Huayi Wang", "Feiyu Jia", "Yukai Qi", "Kangning Yin", "Weishuai Zeng", "Lipeng Chen", "Xi Li", "Ting Wu", "Kailin Li", "Ruoli Dai", "Jingbo Wang", "Lei Han", "Jiangmiao Pang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.20087"
doi: "10.48550/arXiv.2608.20087"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-09-07
---

# Towards Professional Tennis Styles for Humanoid Robots with Adaptive Motion Planning and Tracking

> Tao Huang, Ruofei Liu, Xuchen Tang, Xinyin Zhang, Junli Ren, Huayi Wang, Feiyu Jia, Yukai Qi, Kangning Yin, Weishuai Zeng, Lipeng Chen, Xi Li, Ting Wu, Kailin Li, Ruoli Dai, Jingbo Wang, Lei Han, Jiangmiao Pang · 2026
> [arXiv](https://arxiv.org/abs/2608.20087) · [PDF](https://arxiv.org/pdf/2608.20087)

## Abstract

Humanoid robots have recently demonstrated promising capabilities in real-world ball sports. However, achieving professional motion styles while maintaining strong task performance remains challenging. In this work, we propose AdaPT, an Adaptive Motion Planning and Tracking framework that learns professional tennis serving and rally styles directly from broadcast videos. This hierarchical design is motivated by the key insight that the planner generates stylistic kinematic motions, while the tracker executes them with minimal interference with planning. Despite its effectiveness in simulation, a substantial sim-to-real gap emerges: tracking performance inevitably degrades on real robots, and this degradation is partially overlooked by autoregressive planning and further compounded by noisy perception. To address these issues, our adaptation mechanism improves tracking robustness by learning to track randomized execution speeds, while conditioning the planner on a learned motion-speed adapter to mitigate compounding errors. Real-world experiments on the Unitree G1 demonstrate the effectiveness of our adaptation mechanism in bridging the sim-to-real gap. We further deploy AdaPT policies on the full-size Dobot Atom humanoid robot (1.7m) and demonstrate in-the-wild serving without motion capture. Beyond these results, our real-world experiments reveal both algorithmic and engineering insights for future humanoid ball-sports systems. Videos and code are available on our \href{https://humanoidtennis.github.io/AdaPT/}{project website}.

## TL;DR

Humanoid robots have recently demonstrated promising capabilities in real-world ball sports. However, achieving professional motion styles while maintaining strong task performance remains challenging.

## Related
<!-- [[other-paper-citekey]] -->
