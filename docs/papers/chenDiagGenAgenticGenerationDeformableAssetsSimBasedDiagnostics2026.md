---
citekey: "chenDiagGenAgenticGenerationDeformableAssetsSimBasedDiagnostics2026"
title: "DiagGen: Agentic Generation of Deformable Assets with Sim-based Diagnostics for Robotic Simulation"
authors: ["Guanxiong Chen", "Yiduo Qu", "Qianjun Xia", "Pengyu Jing", "Yixian Cheng", "Bole Ma", "Pengzhi Yang", "Bingyang Zhou", "Ziming Li", "Shashwat Suri", "Gongbo Sun", "Chao Liu", "Peter Yichen Chen", "Ziqiu Zeng", "Fan Shi"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.23103"
doi: "10.48550/arXiv.2609.23103"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-09-22
---

# DiagGen: Agentic Generation of Deformable Assets with Sim-based Diagnostics for Robotic Simulation

> Guanxiong Chen, Yiduo Qu, Qianjun Xia, Pengyu Jing, Yixian Cheng, Bole Ma, Pengzhi Yang, Bingyang Zhou, Ziming Li, Shashwat Suri, Gongbo Sun, Chao Liu, Peter Yichen Chen, Ziqiu Zeng, Fan Shi · 2026
> [arXiv](https://arxiv.org/abs/2609.23103) · [PDF](https://arxiv.org/pdf/2609.23103)

## Abstract

While simulation-ready deformable assets are essential for in-silico robotic manipulation tasks, existing generation frameworks typically assess physical plausibility after generation, leaving an object's simulated response unused as feedback for repairing upstream errors. We present DiagGen, an agentic framework that turns a single in-the-wild image into a simulation-ready deformable asset through a generate--simulate--diagnose--refine loop. DiagGen constructs part-aware geometry and material parameters, then uses a VLM (vision-language model)-based agent to select semantically informative regions, probe them in a physics simulator, observe material responses, and route evidence-backed repair cues to the responsible generation stage. Experiments on 40 assets show that diagnostics provides useful repair cues and can moderately improve the quality of generated deformable assets. Finally, we show that unlike assets generated from visual foundation models which may not be simulatable, DiagGen-generated deformables can be directly dropped into a high-fidelity physical simulator for the planning and simulation of contact-rich pick-and-place tasks. The project's website is https://diaggen.github.io/.

## TL;DR

While simulation-ready deformable assets are essential for in-silico robotic manipulation tasks, existing generation frameworks typically assess physical plausibility after generation, leaving an object's simulated response unused as feedback for repairing upstream errors. We present DiagGen, an agentic framework that turns a single in-the-wild image into a simulation-ready deformable asset through a generate--simulate--diagnose--refine loop.

## Related
<!-- [[other-paper-citekey]] -->
