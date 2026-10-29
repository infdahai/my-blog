---
citekey: "leiMAGNETARMultipathGuidedSpatialPosteriorsTransmitterPoseInference2026"
title: "MAGNETAR: Multipath-Guided Spatial Posteriors for Transmitter Pose Inference in the Upper Mid-Band"
authors: ["Haozhe Lei", "Ruibin Chen", "Yuhan Jiang", "Ali Rasteh", "Aditya Dhananjay", "Sundeep Rangan"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.20670"
doi: "10.48550/arXiv.2609.20670"
tags: [paper, embodied-ai, "cs.RO", "eess.SP"]
status: unread
rating:
created: 2026-09-19
---

# MAGNETAR: Multipath-Guided Spatial Posteriors for Transmitter Pose Inference in the Upper Mid-Band

> Haozhe Lei, Ruibin Chen, Yuhan Jiang, Ali Rasteh, Aditya Dhananjay, Sundeep Rangan · 2026
> [arXiv](https://arxiv.org/abs/2609.20670) · [PDF](https://arxiv.org/pdf/2609.20670)

## Abstract

Robots that localize a radio transmitter need more than a point estimate: in cluttered rooms, one measurement is often consistent with several transmitter locations and, because upper-mid-band antennas are directional, several headings. We present MAGNETAR, which infers a joint posterior over planar transmitter position and heading from a single asynchronous radio-frequency (RF) multipath snapshot, represented by angle-of-arrival and signal-to-noise-ratio estimates, given the room layout and receiver pose. Among our five neural scorers, MAGNETAR adopts a shared 2D U-Net conditioned on each candidate heading, jointly normalizing scores over a discretized position-heading grid. Training uses real-to-sim-calibrated 10 GHz simulations and a small measured subset. Grid-based joint posteriors outperform parametric ones on held-out simulations, the heading-conditioned scorer transfers best to robotic measurements, and fusing joint posteriors improves on fusing position-only marginals.

## TL;DR

Robots that localize a radio transmitter need more than a point estimate: in cluttered rooms, one measurement is often consistent with several transmitter locations and, because upper-mid-band antennas are directional, several headings. We present MAGNETAR, which infers a joint posterior over planar transmitter position and heading from a single asynchronous radio-frequency (RF) multipath snapshot, represented by angle-of-arrival and signal-to-noise-ratio estimates, given the room layout and receiver pose.

## Related
<!-- [[other-paper-citekey]] -->
