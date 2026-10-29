---
citekey: "maInsertAnythingGeneralizableContactRichPrecisionInsertionSimulationReality2026"
title: "InsertAnything: Generalizable Contact-Rich Precision Insertion from Simulation to Reality"
authors: ["Zhenghua Ma", "Xinpan Meng", "Zeyu Liu", "Muyuan Ma", "Hengdi Zhang", "Houcheng Li", "Long Cheng"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.24511"
doi: "10.48550/arXiv.2609.24511"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-23
---

# InsertAnything: Generalizable Contact-Rich Precision Insertion from Simulation to Reality

> Zhenghua Ma, Xinpan Meng, Zeyu Liu, Muyuan Ma, Hengdi Zhang, Houcheng Li, Long Cheng · 2026
> [arXiv](https://arxiv.org/abs/2609.24511) · [PDF](https://arxiv.org/pdf/2609.24511)

## Abstract

Contact-rich precision insertion is a key manipulation skill in robotic assembly. Tight clearances make insertion more sensitive to alignment errors and prone to collisions and jamming, while variations in geometry and clearance across parts further complicate policy reuse. We present a reinforcement learning framework that trains insertion policies entirely in simulation for direct deployment without real-world demonstrations or policy fine-tuning. By combining target poses with compact three-dimensional fingertip force feedback, the policy learns to search for alignment and correct its motion despite errors in the estimated hole position. A decoupled gated reward coordinates alignment and insertion. Force-signal smoothing and state-independent standard deviations stabilize the learning process. The resulting policies perform real-world insertion across multiple hole geometries with a minimum nominal clearance of 0.02 mm and improve success while reducing peak contact forces under hole-position errors. Cross-clearance and cross-geometry evaluations further confirm policy generalization. The system achieved the first perfect score of 20/20 on ManipulationNet's peg-in-hole benchmark under its Human-in-the-Loop protocol, with fully autonomous insertion motions. A single policy trained only on a simulated hexagonal insertion task achieved an overall success rate of 95.0% across eight unseen real-world insertion tasks. These results show that learning entirely in simulation can yield precision insertion skills that can be deployed directly and reused across real-world tasks. The project website (https://mzhsoul.github.io/InsertAnything/) provides open-source simulation and real-robot experiment scripts, assets, and trained checkpoints.

## TL;DR

Contact-rich precision insertion is a key manipulation skill in robotic assembly. Tight clearances make insertion more sensitive to alignment errors and prone to collisions and jamming, while variations in geometry and clearance across parts further complicate policy reuse.

## Related
<!-- [[other-paper-citekey]] -->
