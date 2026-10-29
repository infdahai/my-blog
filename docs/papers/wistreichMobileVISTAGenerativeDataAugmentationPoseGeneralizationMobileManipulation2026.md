---
citekey: "wistreichMobileVISTAGenerativeDataAugmentationPoseGeneralizationMobileManipulation2026"
title: "MobileVISTA: Generative Data Augmentation for Pose Generalization in Mobile Manipulation"
authors: ["Suzannah Wistreich", "Stephen Tian", "Isabella Huang", "Vitor Campagnolo Guizilini", "Sergey Zakharov", "Katherine Liu", "Jiajun Wu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.07511"
doi: "10.48550/arXiv.2610.07511"
tags: [paper, embodied-ai, "cs.CV", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-08
---

# MobileVISTA: Generative Data Augmentation for Pose Generalization in Mobile Manipulation

> Suzannah Wistreich, Stephen Tian, Isabella Huang, Vitor Campagnolo Guizilini, Sergey Zakharov, Katherine Liu, Jiajun Wu · 2026
> [arXiv](https://arxiv.org/abs/2610.07511) · [PDF](https://arxiv.org/pdf/2610.07511)

## Abstract

Mobile manipulators such as humanoid robots are increasingly deployed in dynamic, unstructured environments to perform dexterous manipulation tasks. However, end-to-end manipulation policies trained to imitate demonstration data collected from a single robot pose are brittle: even centimeter-scale deviations in robot pose at deployment can drive ego-centric observations and end-effector trajectories out of the training distribution, leading to sharp drops in performance. We introduce MobileVISTA, a data generation framework that transforms demonstrations captured at canonical poses into diverse, pose-perturbed training data by jointly (1) augmenting egocentric visual observations and (2) retargeting actions to compensate for base pose changes. Unlike prior methods, which assume a camera rigidly mounted off the actuated chain or non-trivial articulated robot geometry largely out of frame, MobileVISTA targets compatibility with egocentric platforms (e.g., humanoids) where the camera is both influenced by and must observe the robot's kinematic chain as it moves. We study MobileVISTA in simulated tasks spanning humanoid and bimanual embodiments, and on a real Galaxea R1 Pro. We find policies trained on MobileVISTA-augmented data demonstrate improved robustness to previously out-of-distribution poses encountered at test time, without additional demonstration collection or a trained generative model. Additionally, we find MobileVISTA's benefit is largest on tested humanoids, where the camera rides the actuated chain and the robot fills much of the frame. Additional videos and appendix can be found on our website: https://mobilevista.github.io

## TL;DR

Mobile manipulators such as humanoid robots are increasingly deployed in dynamic, unstructured environments to perform dexterous manipulation tasks. However, end-to-end manipulation policies trained to imitate demonstration data collected from a single robot pose are brittle: even centimeter-scale deviations in robot pose at deployment can drive ego-centric observations and end-effector trajectories out of the training distribution, leading to sharp drops in performance.

## Related
<!-- [[other-paper-citekey]] -->
