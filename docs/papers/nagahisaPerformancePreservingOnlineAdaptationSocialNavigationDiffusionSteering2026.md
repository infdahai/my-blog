---
citekey: "nagahisaPerformancePreservingOnlineAdaptationSocialNavigationDiffusionSteering2026"
title: "Performance-Preserving Online Adaptation in Social Navigation via Diffusion Steering"
authors: ["Haruto Nagahisa", "Kohei Matsumoto", "Yuki Hyodo", "Ryo Kurazume"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.24317"
doi: "10.48550/arXiv.2609.24317"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-23
---

# Performance-Preserving Online Adaptation in Social Navigation via Diffusion Steering

> Haruto Nagahisa, Kohei Matsumoto, Yuki Hyodo, Ryo Kurazume · 2026
> [arXiv](https://arxiv.org/abs/2609.24317) · [PDF](https://arxiv.org/pdf/2609.24317)

## Abstract

In social navigation, modeling the complex interactions between humans and robots is difficult, and deep reinforcement learning has therefore been actively studied. However, because simulation alone cannot fully reproduce diverse scenarios, robot dynamics, and the social conventions that vary across deployment environments, fine-tuning in the deployment environment is promising. In doing so, learning that preserves the base model's performance is required, so as not to compromise the primary objective of navigation, namely avoiding pedestrians and reaching the destination. In this study, we propose a method that applies diffusion steering via reinforcement learning (DSRL), which trains only the noise policy while keeping the diffusion policy fixed, thereby achieving learning that preserves performance. Furthermore, we integrate diffusion-based RL policies trained with multiple seeds to construct the base policy, improving learning performance. Our evaluation shows that, compared with other methods, the proposed method enables efficient learning while preserving performance, and we confirm flexible behavior control through adaptation to social conventions, as well as its effectiveness on a physical robot through hardware-in-the-loop simulation.

## TL;DR

In social navigation, modeling the complex interactions between humans and robots is difficult, and deep reinforcement learning has therefore been actively studied. However, because simulation alone cannot fully reproduce diverse scenarios, robot dynamics, and the social conventions that vary across deployment environments, fine-tuning in the deployment environment is promising.

## Related
<!-- [[other-paper-citekey]] -->
