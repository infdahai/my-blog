---
citekey: "parkDiscoDemoDiscoveringEfficientDiverseDemonstrationsImitationLearning2026"
title: "DiscoDemo: Discovering Efficient and Diverse Robot Demonstrations for Imitation Learning"
authors: ["Minho Park", "Kinam Kim", "Donghu Kim", "Byungkun Lee", "Dongyoon Hwang", "Yongjae Shin", "Junha Hyung", "Hojoon Lee", "Jaegul Choo"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.32093"
doi: "10.48550/arXiv.2610.32093"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-27
---

# DiscoDemo: Discovering Efficient and Diverse Robot Demonstrations for Imitation Learning

> Minho Park, Kinam Kim, Donghu Kim, Byungkun Lee, Dongyoon Hwang, Yongjae Shin, Junha Hyung, Hojoon Lee, Jaegul Choo · 2026
> [arXiv](https://arxiv.org/abs/2610.32093) · [PDF](https://arxiv.org/pdf/2610.32093)

## Abstract

Behavior cloning for robotic manipulation is highly sensitive to the coverage of its training data, yet collecting diverse successful demonstrations remains costly. We study reinforcement learning (RL) not as a deployable controller, but as a data generator for downstream visuomotor imitation learning. Our key premise is that multiple successful solution modes cover a broader range of successful trajectories than repeatedly collecting a single narrow solution. We introduce DiscoDemo, which trains a privileged latent-conditioned RL generator with a parallel reverse curriculum and a success-gated diversity objective to discover diverse solutions while preserving task success. The trained generator produces multiple successful closed-loop behaviors, which are safety-filtered and exported as a static dataset for downstream imitation learning. Across four manipulation tasks, DiscoDemo produces broader successful-state coverage and improves downstream visuomotor policies in both simulation and the real world. Averaged across tasks, downstream success increases to 62% from 40% for the strongest baseline in simulation, and to 78% from 39% on the real robot, respectively. These results suggest that successful solution diversity improves imitation learning for a pretrained flow-matching VLA and remains complementary to corrective data collection. Project page: https://davian-robotics.github.io/DiscoDemo

## TL;DR

Behavior cloning for robotic manipulation is highly sensitive to the coverage of its training data, yet collecting diverse successful demonstrations remains costly. We study reinforcement learning (RL) not as a deployable controller, but as a data generator for downstream visuomotor imitation learning.

## Related
<!-- [[other-paper-citekey]] -->
