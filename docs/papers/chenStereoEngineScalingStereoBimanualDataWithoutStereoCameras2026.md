---
citekey: "chenStereoEngineScalingStereoBimanualDataWithoutStereoCameras2026"
title: "StereoEngine: Scaling Stereo Bimanual Robot Data without Stereo Cameras"
authors: ["Jason Chen", "I-Chun Arthur Liu", "Gaurav Sukhatme", "Daniel Seita"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.12734"
doi: "10.48550/arXiv.2610.12734"
tags: [paper, embodied-ai, "cs.CV", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-13
---

# StereoEngine: Scaling Stereo Bimanual Robot Data without Stereo Cameras

> Jason Chen, I-Chun Arthur Liu, Gaurav Sukhatme, Daniel Seita · 2026
> [arXiv](https://arxiv.org/abs/2610.12734) · [PDF](https://arxiv.org/pdf/2610.12734)

## Abstract

Stereo vision is increasingly used for robotic manipulation, with a growing body of work incorporating it into Vision-Language-Action (VLA) models. However, the scarcity of large-scale, real-world stereo datasets remains a fundamental bottleneck for scaling such policies. Recent generative monocular-to-stereo methods target settings such as VR content and autonomous driving. No prior work produces realistic synthetic stereo data for robotic manipulation, where stereo supervision has come predominantly from simulation. We propose StereoEngine, which introduces two complementary methods to synthesize stereo data for robotic manipulation. In the first, we warp a monocular (left) video into the right view using estimated depth and inpaint the disoccluded regions with a video diffusion model, lifting monocular demonstrations into stereo pairs without training on real stereo. In the second, we render a stereo pair in simulation and jointly generate both photorealistic views, producing consistent left-right data without any real video as input. StereoEngine outperforms existing baselines in generated stereo quality, and using its synthetic data for policy mid-training or task-specific fine-tuning substantially improves downstream bimanual manipulation. Project website: https://stereoengine.github.io

## TL;DR

Stereo vision is increasingly used for robotic manipulation, with a growing body of work incorporating it into Vision-Language-Action (VLA) models. However, the scarcity of large-scale, real-world stereo datasets remains a fundamental bottleneck for scaling such policies.

## Related
<!-- [[other-paper-citekey]] -->
