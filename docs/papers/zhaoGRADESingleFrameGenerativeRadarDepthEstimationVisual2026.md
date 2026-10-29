---
citekey: "zhaoGRADESingleFrameGenerativeRadarDepthEstimationVisual2026"
title: "GRADE: Single-Frame Generative Radar Depth Estimation Under Visual Degradation"
authors: ["Bin Zhao", "Patrick Chiou", "Nakul Garg"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.10756"
doi: "10.48550/arXiv.2609.10756"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-12
---

# GRADE: Single-Frame Generative Radar Depth Estimation Under Visual Degradation

> Bin Zhao, Patrick Chiou, Nakul Garg · 2026
> [arXiv](https://arxiv.org/abs/2609.10756) · [PDF](https://arxiv.org/pdf/2609.10756)

## Abstract

Dense 3D depth perception fails under smoke, fog, and darkness because optical sensors cannot penetrate airborne particulates. mmWave radar remains usable and measures range accurately under these conditions, but its small aperture limits angular resolution. We present GRADE, which grounds a pretrained generative prior in single-frame radar geometry to estimate high-fidelity metric depth. GRADE first maps raw 4D radar spectra to coarse metric depth. A latent diffusion backbone then recovers structural detail while conditioning every denoising step on this estimate. A pixel-space adapter uses residual camera cues when available and is trained across clear, smoke-degraded, and occluded inputs so the full output approaches the radar-conditioned path as visibility degrades. Trained and evaluated on ~95K frames across 12 buildings with real smoke, GRADE achieves an MAE of 0.303 m in clear scenes and 0.313 m under smoke, outperforming existing baselines. Code and datasets are available at https://phi-lab-rice.github.io/GRADE.

## TL;DR

Dense 3D depth perception fails under smoke, fog, and darkness because optical sensors cannot penetrate airborne particulates. mmWave radar remains usable and measures range accurately under these conditions, but its small aperture limits angular resolution.

## Related
<!-- [[other-paper-citekey]] -->
