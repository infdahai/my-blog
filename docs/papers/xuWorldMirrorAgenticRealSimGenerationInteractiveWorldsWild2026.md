---
citekey: "xuWorldMirrorAgenticRealSimGenerationInteractiveWorldsWild2026"
title: "WorldMirror: Agentic Real-to-Sim Generation of Interactive Worlds from In-the-Wild Robot Demonstrations"
authors: ["Tianling Xu", "Weijie Wan", "Honghao Su", "Kailun Su", "Junyuan Tang", "Huichi Zhou", "Haozheng Zhang", "Qi Xiong", "Ping Luo", "Wenbo Ding", "Tianxing Chen", "Yue Chen"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.31834"
doi: "10.48550/arXiv.2610.31834"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-26
---

# WorldMirror: Agentic Real-to-Sim Generation of Interactive Worlds from In-the-Wild Robot Demonstrations

> Tianling Xu, Weijie Wan, Honghao Su, Kailun Su, Junyuan Tang, Huichi Zhou, Haozheng Zhang, Qi Xiong, Ping Luo, Wenbo Ding, Tianxing Chen, Yue Chen · 2026
> [arXiv](https://arxiv.org/abs/2610.31834) · [PDF](https://arxiv.org/pdf/2610.31834)

## Abstract

Existing approaches for robot learning in simulation often require substantial manual effort to construct scenes and specify tasks, limiting training scalability and data diversity. Meanwhile, in-the-wild robot demonstrations naturally provide diverse and realistic observations of real-world interactions. Leveraging these demonstrations for simulation requires both high-fidelity visual reconstruction and physically consistent interactions. General-purpose agents offer flexible adaptation to diverse scenarios and strong reasoning about 3D spatial relationships, while specialized generative models provide high-fidelity reconstruction of scene appearance and geometry. We introduce WorldMirror, an agentic real-to-sim framework that constructs interactive digital twins from in-the-wild robot demonstrations. Our central idea is to formulate real-to-sim construction as the iterative refinement of an executable world program. A coding agent decomposes the observed scene, plans reconstruction steps, and orchestrates specialized image and 3D generation tools, refining the program through verification feedback. A camera-pose-anchored scene representation organizes the world into static visual context, support geometry, and editable interactive assets while preserving spatial relationships among the scene, objects, and robot. The agent uses this representation to diagnose and correct reconstruction errors, enabling physically consistent interaction and trajectory replay. Experiments on DROID demonstrate that WorldMirror can reconstruct visually faithful and geometrically consistent interactive worlds while preserving the physical validity of recorded robot trajectories.

## TL;DR

Existing approaches for robot learning in simulation often require substantial manual effort to construct scenes and specify tasks, limiting training scalability and data diversity. Meanwhile, in-the-wild robot demonstrations naturally provide diverse and realistic observations of real-world interactions.

## Related
<!-- [[other-paper-citekey]] -->
