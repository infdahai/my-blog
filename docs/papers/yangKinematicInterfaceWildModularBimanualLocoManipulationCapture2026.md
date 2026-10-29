---
citekey: "yangKinematicInterfaceWildModularBimanualLocoManipulationCapture2026"
title: "Kinematic Interface for the Wild: Modular Bimanual Loco-Manipulation Capture from 360$^{\circ}$ Cameras Alone"
authors: ["Benjamin Yang", "Weiying Wang", "Shenggao Li", "Keming Yan", "Sasha Wilkinson", "Zelin Wang", "Yip Fun Yeung", "Lingfeng Sun"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.22809"
doi: "10.48550/arXiv.2609.22809"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-22
---

# Kinematic Interface for the Wild: Modular Bimanual Loco-Manipulation Capture from 360$^{\circ}$ Cameras Alone

> Benjamin Yang, Weiying Wang, Shenggao Li, Keming Yan, Sasha Wilkinson, Zelin Wang, Yip Fun Yeung, Lingfeng Sun · 2026
> [arXiv](https://arxiv.org/abs/2609.22809) · [PDF](https://arxiv.org/pdf/2609.22809)

## Abstract

A wrist-mounted camera for UMI-style data collection must do two jobs: record the manipulation and localize in the scene. Most handheld devices localize online from workspace-facing views crowded by hands and objects, or add dedicated tracking hardware. Room-scale bimanual capture therefore still tends to instrument the operator or the scene for accurate localization. We present KIWI (Kinematic Interface for the Wild), a capture kit whose only electronics are off-the-shelf cameras. Our core system splits the two jobs across the two lenses of a 360-degree camera. The rear lens faces the room and builds a shared metric map that registers both hands, and an optional head camera, in one frame without workspace co-visibility; the front lens records the manipulation, and offline IMU fusion bridges front-lens tracking loss. Through our quick-release plate, the camera module attaches to chopstick grippers, parallel-jaw grippers, hand-wrist mounts, or robot flanges. Across six bimanual recordings, combining the rear and front lenses failed to localize only 0.1% of query frames, whereas front-only bimanual feature alignment failed on 24.8% of frames and lost one recording entirely; against evaluation fiducials, localization error stayed within 4.5 mm. KIWI's recovered poses were sufficiently consistent for the four wrist streams alone to reconstruct the scene as a 3D Gaussian splat.

## TL;DR

A wrist-mounted camera for UMI-style data collection must do two jobs: record the manipulation and localize in the scene. Most handheld devices localize online from workspace-facing views crowded by hands and objects, or add dedicated tracking hardware.

## Related
<!-- [[other-paper-citekey]] -->
