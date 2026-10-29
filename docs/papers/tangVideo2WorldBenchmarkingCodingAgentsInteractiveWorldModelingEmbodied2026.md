---
citekey: "tangVideo2WorldBenchmarkingCodingAgentsInteractiveWorldModelingEmbodied2026"
title: "Video2World: Benchmarking Coding Agents for Interactive World Modeling from Embodied Videos"
authors: ["Jinzhou Tang", "Zijun Zhang", "Jing Yang", "Yuchen Yan", "Kun Zhou", "Lingjun Mao", "Ruobing Han", "Jinglin Cao", "Wenpeng Xu", "Lukun He", "Minghao Fu", "Fan Feng", "Biwei Huang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.04432"
doi: "10.48550/arXiv.2610.04432"
tags: [paper, embodied-ai, "cs.AI", "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-07
---

# Video2World: Benchmarking Coding Agents for Interactive World Modeling from Embodied Videos

> Jinzhou Tang, Zijun Zhang, Jing Yang, Yuchen Yan, Kun Zhou, Lingjun Mao, Ruobing Han, Jinglin Cao, Wenpeng Xu, Lukun He, Minghao Fu, Fan Feng, Biwei Huang · 2026
> [arXiv](https://arxiv.org/abs/2610.04432) · [PDF](https://arxiv.org/pdf/2610.04432)

## Abstract

Building interactive simulators from real-world observations is a promising way to scale embodied data, but current pipelines still rely heavily on manual environment construction and calibration. We study whether frontier foundation models and coding agents can automate this process end to end. We formulate \emph{autonomous video-to-simulation} as a software engineering task in which an agent observes an embodied video, constructs the corresponding simulated environment and robot behavior, and iteratively refines the result through execution feedback. To evaluate this capability, we introduce \textbf{Video2World}, a benchmark comprising 222 reconstruction instances derived from 189 robot and human demonstration videos. Video2World measures reconstructed worlds along geometric fidelity, dynamic fidelity, and functional correctness, capturing spatial perception, physical reasoning, and executable interaction. Evaluating 9 frontier coding-agent systems reveals a sharp improvement in Task success beginning with Claude Opus 5, rising from below 5\% to over 15\%, while substantial gaps to human-assisted reconstruction remain. We further find that worlds that look better could work worse: better visual fidelity does not always lead to higher task success. This echoes the broader gap between perceptual realism and factual correctness observed in generative models.

## TL;DR

Building interactive simulators from real-world observations is a promising way to scale embodied data, but current pipelines still rely heavily on manual environment construction and calibration. We study whether frontier foundation models and coding agents can automate this process end to end.

## Related
<!-- [[other-paper-citekey]] -->
