---
citekey: "wangI2CDDirectImageConvexDecompositionSimulationReadyCollision2026"
title: "I2CD: Direct Image-to-Convex Decomposition for Simulation-Ready Collision Geometry"
authors: ["Qian Wang", "Liam Merz Hoffmeister", "Brian Scassellati", "Daniel Rakita"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.03453"
doi: "10.48550/arXiv.2610.03453"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-06
---

# I2CD: Direct Image-to-Convex Decomposition for Simulation-Ready Collision Geometry

> Qian Wang, Liam Merz Hoffmeister, Brian Scassellati, Daniel Rakita · 2026
> [arXiv](https://arxiv.org/abs/2610.03453) · [PDF](https://arxiv.org/pdf/2610.03453)

## Abstract

Physics simulators and motion planners require convex collision geometry, yet image-to-3D generative models output dense, frequently non-manifold visual meshes. Bridging the two today takes a slow, brittle reconstruct-then-decompose pipeline of repair, decimation, and approximate convex decomposition. We present I2CD, which predicts a convex decomposition directly from a single RGB image. Rather than train a new image-to-3D model, I2CD freezes the pretrained Hunyuan3D-2 image-conditioned diffusion transformer and shape decoder and trains only a lightweight cross-attention head (38M parameters, under ten GPU-hours) whose learned "convex-slot" tokens emit the halfplane parameters of $K$ convex polytopes. The output is compact, convex by construction, and loads into physics engines without any post-processing, in ${\sim}0.5$s per image. On $227$ held-out OmniObject3D and Google Scanned Objects instances, I2CD attains the highest volumetric IoU among eight reconstruct-then-decompose pipelines while running $6$-$37\times$ faster end-to-end. In a cross-simulator study in MuJoCo, PyBullet, Genesis, and Isaac Sim, every engine uses I2CD geometry as delivered, whereas raw generated meshes "load" everywhere but are silently replaced by a different collision shape in most cases or need seconds to minutes of per-object preprocessing. On a physical xArm7, I2CD produces planner-ready geometry for a $20$-object cluttered scene in $11$s versus $328$s for the strongest baseline, at comparable pick-and-place execution success ($85$ vs. $90$ of $100$ trials).

## TL;DR

Physics simulators and motion planners require convex collision geometry, yet image-to-3D generative models output dense, frequently non-manifold visual meshes. Bridging the two today takes a slow, brittle reconstruct-then-decompose pipeline of repair, decimation, and approximate convex decomposition.

## Related
<!-- [[other-paper-citekey]] -->
