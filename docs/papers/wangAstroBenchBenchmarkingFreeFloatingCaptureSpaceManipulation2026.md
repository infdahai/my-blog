---
citekey: "wangAstroBenchBenchmarkingFreeFloatingCaptureSpaceManipulation2026"
title: "AstroBench: Benchmarking Free-Floating Capture and Space Robotic Manipulation"
authors: ["Zizhe Wang", "Jia Deng", "Xin Lu", "Zehao Jia", "Yi Huang", "Yao Zhu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.31064"
doi: "10.48550/arXiv.2610.31064"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-24
---

# AstroBench: Benchmarking Free-Floating Capture and Space Robotic Manipulation

> Zizhe Wang, Jia Deng, Xin Lu, Zehao Jia, Yi Huang, Yao Zhu · 2026
> [arXiv](https://arxiv.org/abs/2610.31064) · [PDF](https://arxiv.org/pdf/2610.31064)

## Abstract

Capturing a loose object inside a spacecraft requires a robot to approach a target that can translate and rotate, and whose motion changes when contact is made. These conditions motivate evaluation beyond manipulation of supported objects. We introduce AstroBench, an open benchmark for free-floating capture and space robotic manipulation with a fixed-base arm. The task suite combines four initial-motion tracks with sample-storage operations based on MELFI hardware and cap and captive-screw servicing based on the Robotic Refueling Mission. The two workcells provide nine task definitions and 29 task-target combinations. A metadata-filtered Objaverse inventory supplies 8,414 object instances for asset expansion, alongside five cabin visual contexts and versioned task instructions. We report two acquisition-focused experiments using existing checkpoints. A frozen $π_{0.5}$ DROID joint-position policy captures 2 of 200 static targets and 4 of 200 moving targets across twenty object identities. A cube-specific ACT policy captures 8 of 10 static targets and 6 of 10 moving targets in a separate experiment. Each experiment retains its recorded observation, action and capture configuration. The results document difficult direct transfer for the tested generalist checkpoint and successful task-specific capture behavior, while identifying concrete settings for studying motion-aware perception and contact-sensitive control. Code, task definitions and editable workcell assets are available at https://github.com/AstroUpLab/AstroBench.

## TL;DR

Capturing a loose object inside a spacecraft requires a robot to approach a target that can translate and rotate, and whose motion changes when contact is made. These conditions motivate evaluation beyond manipulation of supported objects.

## Related
<!-- [[other-paper-citekey]] -->
