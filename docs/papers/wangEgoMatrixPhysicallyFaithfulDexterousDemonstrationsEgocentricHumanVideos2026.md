---
citekey: "wangEgoMatrixPhysicallyFaithfulDexterousDemonstrationsEgocentricHumanVideos2026"
title: "EgoMatrix: Physically Faithful Dexterous Robot Demonstrations from Egocentric Human Videos"
authors: ["Ziheng Wang", "Yanming Shao", "Ting Mao", "Kaihan Chen", "Yiqun Wang", "Xuanye Wu", "Yao Mu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.18822"
doi: "10.48550/arXiv.2610.18822"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-18
---

# EgoMatrix: Physically Faithful Dexterous Robot Demonstrations from Egocentric Human Videos

> Ziheng Wang, Yanming Shao, Ting Mao, Kaihan Chen, Yiqun Wang, Xuanye Wu, Yao Mu · 2026
> [arXiv](https://arxiv.org/abs/2610.18822) · [PDF](https://arxiv.org/pdf/2610.18822)

## Abstract

Egocentric human videos offer a scalable alternative to robot teleoperation for collecting dexterous manipulation data. However, two challenges limit their use as reliable training data: accurate hand-object interaction (HOI) reconstruction from monocular RGB and high-quality robot demonstrations, especially visual observations. We present EgoMatrix, an end-to-end data engine that converts monocular egocentric human videos into bimanual dexterous trajectories and paired robot observation videos, with the trajectories directly replayable on real robots. It reconstructs HOI with emphasis on relative geometry and contact rather than exact metric scene recovery, then uses retargeting and reinforcement learning (RL) to reproduce the demonstrated tasks in simulation. We jointly render robot hands and objects from these simulated trajectories to produce physically faithful observations synchronized with state and control records. Rendering the same trajectories in diverse, task-compatible backgrounds expands paired training data while preserving robot-object motion and contact. Across TACO, OakInk2, and self-collected data, EgoMatrix achieves 54.84% end-to-end success in simulation versus 14.52% for the strongest baseline. Reconstruction reaches state-of-the-art performance on most metrics of the two public benchmarks. Qualitative results show more faithful hand-object interactions than prior methods, while feature-space analysis shows closer alignment with real-robot observations than GPT-6 Astra. Our project page is available at https://spikew726.github.io/EgoMatrix/.

## TL;DR

Egocentric human videos offer a scalable alternative to robot teleoperation for collecting dexterous manipulation data. However, two challenges limit their use as reliable training data: accurate hand-object interaction (HOI) reconstruction from monocular RGB and high-quality robot demonstrations, especially visual observations.

## Related
<!-- [[other-paper-citekey]] -->
