---
citekey: "huWorkhorseLearningRobustWholeBodyHumanoidLocoManipulation2026"
title: "Workhorse: Learning Robust Whole-Body Humanoid Loco-Manipulation from Human Data"
authors: ["Songbo Hu", "Qiayuan Liao", "Yufeng Chi", "Kevin Zakka", "Yakun Sophia Shao", "Pieter Abbeel", "Koushil Sreenath"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.09117"
doi: "10.48550/arXiv.2610.09117"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-09
---

# Workhorse: Learning Robust Whole-Body Humanoid Loco-Manipulation from Human Data

> Songbo Hu, Qiayuan Liao, Yufeng Chi, Kevin Zakka, Yakun Sophia Shao, Pieter Abbeel, Koushil Sreenath · 2026
> [arXiv](https://arxiv.org/abs/2610.09117) · [PDF](https://arxiv.org/pdf/2610.09117)

## Abstract

Humanoid robots still struggle to plan contact-rich whole-body manipulation from egocentric RGB and proprioception. Workhorse learns such manipulation from robot-free human demonstrations. A visual planner predicts five-link targets: the poses of the torso, both wrists, and both feet. A reinforcement-learning whole-body tracker follows them on the robot. Both policies train separately on the same recorded human poses, without retargeting. We augment the training data of each policy to imitate the errors that the other makes at deployment. On a real Unitree G1, Workhorse sorts boxes with its hands and a kick, catches a thrown box, and topples and climbs a suitcase. During box sorting, we show recoveries after a person pushes the robot or takes the box away. In a simulated copy of the demonstration room, the system completes box sorting in 77% of episodes, and in 64% under 40 N.s pushes. With both policies retrained from the same demonstrations, a simulated second humanoid completes box sorting in 83% of episodes without pushes.

## TL;DR

Humanoid robots still struggle to plan contact-rich whole-body manipulation from egocentric RGB and proprioception. Workhorse learns such manipulation from robot-free human demonstrations.

## Related
<!-- [[other-paper-citekey]] -->
