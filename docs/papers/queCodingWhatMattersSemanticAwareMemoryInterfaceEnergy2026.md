---
citekey: "queCodingWhatMattersSemanticAwareMemoryInterfaceEnergy2026"
title: "Coding What Matters: A Semantic-Aware Memory Interface for Energy-Efficient Perception in Autonomous Vehicles"
authors: ["Haohua Que", "Handong Yao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.29000"
doi: "10.48550/arXiv.2608.29000"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-02
---

# Coding What Matters: A Semantic-Aware Memory Interface for Energy-Efficient Perception in Autonomous Vehicles

> Haohua Que, Handong Yao · 2026
> [arXiv](https://arxiv.org/abs/2608.29000) · [PDF](https://arxiv.org/pdf/2608.29000)

## Abstract

Autonomous vehicles stream high-resolution surround-camera frames into memory before perception runs. This sensor-to-memory path consumes energy when cells store ones and adjacent bytes toggle on the data bus, so its cost follows bit-1 density and switching activity rather than pixel semantics. We present MotiMem-Omega, a semantic-aware memory-interface coder that lowers this cost while preserving perception predictions. Its semantic importance field protects traffic participants, especially vulnerable road users, while assigning lower fidelity to sky and empty background. Cross-dataset bit-sensitivity sweeps determine class weights, with a safety floor for pedestrians, cyclists, and motorcyclists. Each image block then selects a precision tier by minimizing a joint energy-distortion cost. When ego pose is available, a motion-compensated prior carries protected regions between frames. We estimate interface-energy reduction from the two measured proxies using a coefficient-swept memory-energy model. Across 29 detectors on 12 driving datasets, 5 occupancy models, and 5 segmentation networks, MotiMem-Omega retains about 90% of detection mean average precision, 91% of vulnerable-road-user recall, over 98% of occupancy accuracy, and the strongest segmentation retention among energy-reducing methods. It reduces front-camera bit-1 density by 52%, corresponding to a modeled memory-interface energy reduction near 36%, with a lower end of 27% under the literature coefficient sweep. It also gives higher retention than the baseline and energy-matched truncation at the same or lower bit-1 density, whereas image codecs preserve accuracy without reducing memory-interface energy.

## TL;DR

Autonomous vehicles stream high-resolution surround-camera frames into memory before perception runs. This sensor-to-memory path consumes energy when cells store ones and adjacent bytes toggle on the data bus, so its cost follows bit-1 density and switching activity rather than pixel semantics.

## Related
<!-- [[other-paper-citekey]] -->
