---
citekey: "guoWorldsOneDemoSyntheticDataEngineLearningOpen2026"
title: "Worlds in One Demo: A Synthetic Data Engine for Learning Open-World Mobile Manipulation"
authors: ["Lingxiao Guo", "Huanyu Li", "Guanya Shi"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2607.13154"
doi: "10.48550/arXiv.2607.13154"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# Worlds in One Demo: A Synthetic Data Engine for Learning Open-World Mobile Manipulation

> Lingxiao Guo, Huanyu Li, Guanya Shi · 2026
> [arXiv](https://arxiv.org/abs/2607.13154) · [PDF](https://arxiv.org/pdf/2607.13154)

## Abstract

Learning open-world mobile manipulation policies requires vast data to achieve spatial generalization, long-horizon robustness, and scene generalization. Current prevailing data collection paradigms, teleoperation and UMI, demand prohibitive human effort and cost at scale. To scale beyond the limits of manual data collection, we seek to maximize the value of each human demonstration by scalable data generation. To this end, we introduce WANDA: learning open-World mobile mANipulation from one demonstration via a synthetic DAta engine. WANDA first reconstructs background Gaussian splats and robot-object interaction trajectories from source RGBD observations, as a world substrate for later planning and rendering. It then rearranges contact-rich robot-object interaction segments into extensive spatial configurations, utilizing whole-body motion planning to chain them into new trajectories. To enhance long-horizon robustness, it applies Corrective State Expansion to increase the robot and object state diversity at different stages of mobile manipulation. To unlock cross-environment generalization, trajectories are synthesized on diverse generated 3D worlds from everyday photos. Furthermore, we synthesize photo-realistic observations by compositing rendered robot and object meshes with Gaussian splatting backgrounds. We evaluate our approach on extensive simulation and real-world tasks in various scenes. Experiments show that policies trained with WANDA achieve long-horizon robustness, broad spatial generalization and cross-environment generalization from one real demonstration. Moreover, WANDA naturally supports cross-embodiment data generation, validated by zero-shot deployment on another mobile manipulator with a distinct morphology.

## TL;DR

Learning open-world mobile manipulation policies requires vast data to achieve spatial generalization, long-horizon robustness, and scene generalization. Current prevailing data collection paradigms, teleoperation and UMI, demand prohibitive human effort and cost at scale.

## Related
<!-- [[other-paper-citekey]] -->
