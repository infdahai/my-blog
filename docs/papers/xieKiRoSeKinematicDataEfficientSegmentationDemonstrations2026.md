---
citekey: "xieKiRoSeKinematicDataEfficientSegmentationDemonstrations2026"
title: "KiRoSe: Using Kinematic Data for Efficient Segmentation of Robot Demonstrations"
authors: ["Shuangyu Xie", "Kaiyuan Chen", "Muhammad Zubair Irshad", "Richard Cheng", "Sergey Zakharov", "Ken Goldberg"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.31801"
doi: "10.48550/arXiv.2610.31801"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-27
---

# KiRoSe: Using Kinematic Data for Efficient Segmentation of Robot Demonstrations

> Shuangyu Xie, Kaiyuan Chen, Muhammad Zubair Irshad, Richard Cheng, Sergey Zakharov, Ken Goldberg · 2026
> [arXiv](https://arxiv.org/abs/2610.31801) · [PDF](https://arxiv.org/pdf/2610.31801)

## Abstract

Segmenting robot demonstration data into disjoint temporal and semantic subsegments is valuable for learning, cleaning, retrieval, and analysis. Segmentation is often performed manually in a tedious and error prone process. Multimodal Large Language Models (MLLMs) have the potential for automating this process, but directly ingesting raw multi camera video streams into MLLMs can be costly and can quickly exhaust context windows. In this paper, we introduce KiRoSe (Kinematics for Robot Segmentation), a novel framework that focuses on the companion stream of robot kinematic data. Inspired by the principle of classical entropy coding, such as Huffman coding, where frequently occurring symbols are represented more compactly, we propose Sparse Motion Tokens (SMTs), a discrete kinematic vocabulary designed to compactly represent recurring, temporally localized motion patterns, which we refer to as kinematic events. SMTs are learned by encoding kinematic trajectories with temporal segment supervision and quantizing the resulting features. We use increasingly available robot demonstration subtask annotations to supervise an open language model to interpret the resulting token sequences. Evaluation against human labeled segmentation shows that KiRoSe can substantially outperform baseline segmentation methods in F1 quality and transfers zero shot to unseen robot embodiments and egocentric human motion, while preserving the language models open vocabulary knowledge. Beyond segmentation, KiRoSe tracks task progress on an unseen robot and detects when an action is being reversed.(website: https://berkeleyautomation.github.io/kirose/)

## TL;DR

Segmenting robot demonstration data into disjoint temporal and semantic subsegments is valuable for learning, cleaning, retrieval, and analysis. Segmentation is often performed manually in a tedious and error prone process.

## Related
<!-- [[other-paper-citekey]] -->
