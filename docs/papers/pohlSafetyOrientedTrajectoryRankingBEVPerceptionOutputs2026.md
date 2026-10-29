---
citekey: "pohlSafetyOrientedTrajectoryRankingBEVPerceptionOutputs2026"
title: "Safety-Oriented Trajectory Ranking from BEV Perception Outputs"
authors: ["Leon Pohl", "Martin Frauendorfer", "Corinna Schmitt", "Mirko Maehlisch"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.14066"
doi: "10.48550/arXiv.2610.14066"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-14
---

# Safety-Oriented Trajectory Ranking from BEV Perception Outputs

> Leon Pohl, Martin Frauendorfer, Corinna Schmitt, Mirko Maehlisch · 2026
> [arXiv](https://arxiv.org/abs/2610.14066) · [PDF](https://arxiv.org/pdf/2610.14066)

## Abstract

Bird's-Eye-View (BEV) representations are increasingly used as compact inputs for autonomous driving perception and planning. However, lightweight and interpretable methods for evaluating candidate ego trajectories directly on BEV outputs remain useful for vehicular safety workflows, rapid prototyping, and human-in-the-loop validation. This paper presents a modular trajectory ranking pipeline that consumes BEVFusion object detections and map segmentations derived from nuScenes sensor data and ranks manually specified candidate trajectories according to safety-first criteria. The ranking prioritizes avoiding collisions and walkway violations, then smaller end distance to the target, and finally path efficiency. To study whether these rule-based rankings resemble human judgment, we created seven BEV traffic scenarios and compared the script output with preferences from a survey of 21 participants. Across 146 pairwise votes, 124 matched the trajectory ranked first by the evaluator, corresponding to an overall agreement of 84.9 %. The results indicate that simple BEV-centric safety heuristics can approximate human preferences in constrained trajectory choice tasks while remaining transparent enough for analysis, dataset curation, and autonomous driving studies.

## TL;DR

Bird's-Eye-View (BEV) representations are increasingly used as compact inputs for autonomous driving perception and planning. However, lightweight and interpretable methods for evaluating candidate ego trajectories directly on BEV outputs remain useful for vehicular safety workflows, rapid prototyping, and human-in-the-loop validation.

## Related
<!-- [[other-paper-citekey]] -->
