---
citekey: "luoSceneRigAgenticSystemSimulationReady3DSceneReconstruction2026"
title: "SceneRig: An Agentic System for Simulation-Ready 3D Scene Reconstruction from Single Images"
authors: ["Rundong Luo", "Yunong Liu", "Di Cao", "Matthew Tancik", "Shyamal Buch", "Colton Stearns", "Wenqi Xian"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.28585"
doi: "10.48550/arXiv.2610.28585"
tags: [paper, embodied-ai, "cs.AI", "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-24
---

# SceneRig: An Agentic System for Simulation-Ready 3D Scene Reconstruction from Single Images

> Rundong Luo, Yunong Liu, Di Cao, Matthew Tancik, Shyamal Buch, Colton Stearns, Wenqi Xian · 2026
> [arXiv](https://arxiv.org/abs/2610.28585) · [PDF](https://arxiv.org/pdf/2610.28585)

## Abstract

Simulation is a powerful tool for robotics, but building diverse, simulation-ready scenes at scale remains difficult. Reconstructing scenes from single images is a promising alternative, but visual similarity alone is insufficient: objects must also be recovered, accurately placed, and physically grounded. Existing methods that rely on post-hoc physics settling often misplace objects, producing scenes that look correct but behave poorly under manipulation. We present SceneRig, an agentic system that turns a single image into an editable, simulation-ready scene. SceneRig combines geometric, visual, and physical tools to reconstruct a faithful 3D scene. An agent then performs edit-and-validate loops inside a physics simulator to achieve physical stability. Across diverse inputs, SceneRig improves instance segmentation, object-centric appearance, and 3D placement while keeping the reconstructed scenes physically stable. Furthermore, SceneRig is effective for downstream robotics: its scenes predict real-robot policy outcomes more accurately than the baseline method and more reliably support replay of recorded manipulations without trajectory adaptation.

## TL;DR

Simulation is a powerful tool for robotics, but building diverse, simulation-ready scenes at scale remains difficult. Reconstructing scenes from single images is a promising alternative, but visual similarity alone is insufficient: objects must also be recovered, accurately placed, and physically grounded.

## Related
<!-- [[other-paper-citekey]] -->
