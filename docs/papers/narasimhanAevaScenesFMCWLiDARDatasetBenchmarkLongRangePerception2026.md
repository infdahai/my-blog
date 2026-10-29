---
citekey: "narasimhanAevaScenesFMCWLiDARDatasetBenchmarkLongRangePerception2026"
title: "AevaScenes: An FMCW LiDAR Dataset and Benchmark for Long-Range Perception"
authors: ["Gautham Narayan Narasimhan", "Heethesh Vhavle", "Kumar Bhargav Viswanatha", "James Reuther", "Deva Ramanan"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.33230"
doi: "10.48550/arXiv.2609.33230"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# AevaScenes: An FMCW LiDAR Dataset and Benchmark for Long-Range Perception

> Gautham Narayan Narasimhan, Heethesh Vhavle, Kumar Bhargav Viswanatha, James Reuther, Deva Ramanan · 2026
> [arXiv](https://arxiv.org/abs/2609.33230) · [PDF](https://arxiv.org/pdf/2609.33230)

## Abstract

FMCW LiDAR measures per-point radial Doppler velocity alongside range, providing a motion cue unavailable in conventional time-of-flight sensors. Exploiting this signal at long range remains understudied. We present an FMCW LiDAR dataset of 575 sequences (57.5K frames) with over 8 million annotated 3D boxes across 16 detection classes and per-point labels across 24 semantic classes, captured by six commercial FMCW LiDAR sensors and six paired 4K cameras across eight Bay Area cities, including 237 nighttime sequences, with annotations extending to 400m. We define a benchmark with three tasks: 3D object detection, scene flow estimation, and semantic segmentation. Detection and scene flow are evaluated across three range bins to 400m, with a public evaluation server. We explore the impact of Doppler measurements on flagship recognition tasks, and find significant improvements up to 2X in detection AP of far-away vehicles and pedestrians, particularly in low-latency single-frame settings. We similarly find scene flow accuracy is significantly improved with Doppler measurements across all ranges. Our dataset and benchmark have been publicly released at https://scenes.aeva.com.

## TL;DR

FMCW LiDAR measures per-point radial Doppler velocity alongside range, providing a motion cue unavailable in conventional time-of-flight sensors. Exploiting this signal at long range remains understudied.

## Related
<!-- [[other-paper-citekey]] -->
