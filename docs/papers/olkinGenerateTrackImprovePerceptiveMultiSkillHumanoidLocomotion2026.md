---
citekey: "olkinGenerateTrackImprovePerceptiveMultiSkillHumanoidLocomotion2026"
title: "Generate, Track, Improve: Perceptive Multi-Skill Humanoid Locomotion with RL-Fine-Tuned Motion Generators"
authors: ["Zachary Olkin", "William D. Compton", "Aaron D. Ames"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.31577"
doi: "10.48550/arXiv.2609.31577"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-29
---

# Generate, Track, Improve: Perceptive Multi-Skill Humanoid Locomotion with RL-Fine-Tuned Motion Generators

> Zachary Olkin, William D. Compton, Aaron D. Ames · 2026
> [arXiv](https://arxiv.org/abs/2609.31577) · [PDF](https://arxiv.org/pdf/2609.31577)

## Abstract

General purpose humanoids require locomotion controllers that are multi-skill, perceptive, dynamic, and robust enough to go anywhere humans can. In this work, we present a two layer locomotion architecture: (1) a perceptive flow matching motion generator plans whole body trajectories from raw depth images while a (2) perceptive tracking policy trained with control-guided RL follows these motions. Both policies are trained on a library of terrain consistent motion clips created with dynamically optimized human data which yields both accurate velocity tracking and terrain consistent references. Our central contribution is a simple yet effective off-policy RL fine tuning loop that improves the motion generator. A structured search method is used with the generator to gather data for advantage weighted regression. This off-policy loop is much more sample efficient than on-policy residual fine tuning and improves terrain consistency on unseen geometries and skill compositions. We find that successful terrain traversals increased by up to 25 percentage points and skill selection improved by up to 80 percentage points. By using raw depth images to perceive the environment no odometry or height maps are needed, and outdoor deployment is easy. With two cameras, the policy can see terrain coming from further away and adjust its velocity regardless of the commanded speed so it can traverse the terrain. A single policy pair enables a Unitree G1 humanoid to walk, run, stand, jump on and off of boxes, and traverse stairs in outdoor environments. Project page: https://zolkin1.github.io/generate-track-improve/

## TL;DR

General purpose humanoids require locomotion controllers that are multi-skill, perceptive, dynamic, and robust enough to go anywhere humans can. In this work, we present a two layer locomotion architecture: (1) a perceptive flow matching motion generator plans whole body trajectories from raw depth images while a (2) perceptive tracking policy trained with control-guided RL follows these motions.

## Related
<!-- [[other-paper-citekey]] -->
