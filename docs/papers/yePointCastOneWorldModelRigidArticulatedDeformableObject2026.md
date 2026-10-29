---
citekey: "yePointCastOneWorldModelRigidArticulatedDeformableObject2026"
title: "PointCast: One World Model for Rigid, Articulated, and Deformable Object Manipulation"
authors: ["Hantao Ye", "Ross Worobel", "Zhuoli Xie", "Mingen Li", "Houjian Yu", "Youngjin Hong", "Changhyun Choi"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.28393"
doi: "10.48550/arXiv.2609.28393"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-25
---

# PointCast: One World Model for Rigid, Articulated, and Deformable Object Manipulation

> Hantao Ye, Ross Worobel, Zhuoli Xie, Mingen Li, Houjian Yu, Youngjin Hong, Changhyun Choi · 2026
> [arXiv](https://arxiv.org/abs/2609.28393) · [PDF](https://arxiv.org/pdf/2609.28393)

## Abstract

World models are useful for robotic manipulation because robots can predict how actions change the states of objects before executing them. We present PointCast, a point-set world model that spans rigid, articulated, and deformable object manipulation. Its state is a set of 3D points on the object and the end-effector, mesh-free and topology-agnostic. Each point keeps its identity and is supervised on its own trajectory, which teaches the model where every point goes rather than only the shape the points form. Its backbone is a diffusion transformer that denoises a short window of future point positions, conditioned on the points' recent history and the commanded end-effector motion. The backbone's attention alternates between local and global, and cross-attention to the end-effector carries the coupling. This one architecture at 19.8M parameters and one training recipe cover four regimes, rigid objects, cloth, rope, and multi-joint cabinets, with a separate checkpoint trained for each. Trained on randomized simulation and scored against four baselines on the same metric, it is best on three of four regimes and second on rigid. Trained on a real-world robot teleoperation dataset, it has the lowest mean error in four of its six categories, is second in the other two, and improves on the dataset's own model in all six; zero-shot, its simulation checkpoints are best on two of four captures. Frozen inside sampling-based model-predictive control at one network evaluation per window, it plans four simulated tasks over 64 episodes, competitive with or outperforming every baseline on each. Project website at https://pointcast-wm.github.io.

## TL;DR

World models are useful for robotic manipulation because robots can predict how actions change the states of objects before executing them. We present PointCast, a point-set world model that spans rigid, articulated, and deformable object manipulation.

## Related
<!-- [[other-paper-citekey]] -->
