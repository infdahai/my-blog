---
citekey: "agarwalCOBALTCrowdsourcingLearningCloudBasedTeleoperationSmartphones2026"
title: "COBALT: Crowdsourcing Robot Learning via Cloud-Based Teleoperation with Smartphones"
authors: ["Ayush Agarwal", "Ansh Gandhi", "Jeremy A. Collins", "Omar Rayyan", "Aryan Sarswat", "Ranjani Koushik", "Masoud Moghani", "Ajay Mandlekar", "Animesh Garg"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2605.19138"
doi: "10.48550/arXiv.2605.19138"
tags: [paper, embodied-ai, "cs.AI", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# COBALT: Crowdsourcing Robot Learning via Cloud-Based Teleoperation with Smartphones

> Ayush Agarwal, Ansh Gandhi, Jeremy A. Collins, Omar Rayyan, Aryan Sarswat, Ranjani Koushik, Masoud Moghani, Ajay Mandlekar, Animesh Garg · 2026
> [arXiv](https://arxiv.org/abs/2605.19138) · [PDF](https://arxiv.org/pdf/2605.19138)

## Abstract

The scarcity of large-scale, high-quality demonstration data remains a bottleneck in scaling imitation learning for robotic manipulation. We present COBALT, a teleoperation platform designed to democratize robot learning at scale both in simulation and in the real world. By leveraging vectorized environments, our scalable, load-balanced infrastructure supports concurrent teleoperation by multiple users on a single GPU, yielding a significant reduction in teleoperation cost. Operators can connect from nearly anywhere on Earth using commonly available devices, including single or dual smartphones, VR headsets, 3D mice, and keyboards. An inmemory data cache and efficient video streaming keep control and rendering synchronous, sustaining dozens of concurrent users at 20 Hz with sub-100 ms end-to-end latency for up to 8 concurrent users per GPU. We also demonstrate stable operation supporting 256 simulated clients across 8 GPUs, underscoring the system's ability to scale across hardware and within individual servers. We perform a comprehensive user study showing that phone-based teleoperation performs comparably to or better than specialized hardware, enabling faster, more ergonomic data collection. To ensure data quality, COBALT logs a suite of real-time metrics to automatically filter suboptimal demonstrations. We further demonstrate that a structured user training curriculum significantly improves data collection quality. Guided by insights from our user study, we crowdsource the collection of a large-scale, high-quality pilot dataset with 7500+ demonstrations (50+ hours) collected with smartphones across nine countries over five days. We validate the dataset's quality by training state-of-the-art imitation learning algorithms. Please visit https://cobalt-teleop.github.io/ for more details.

## TL;DR

The scarcity of large-scale, high-quality demonstration data remains a bottleneck in scaling imitation learning for robotic manipulation. We present COBALT, a teleoperation platform designed to democratize robot learning at scale both in simulation and in the real world.

## Related
<!-- [[other-paper-citekey]] -->
