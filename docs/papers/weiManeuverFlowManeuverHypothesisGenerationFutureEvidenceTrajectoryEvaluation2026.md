---
citekey: "weiManeuverFlowManeuverHypothesisGenerationFutureEvidenceTrajectoryEvaluation2026"
title: "ManeuverFlow: Maneuver Hypothesis Generation with Future Evidence for Trajectory Evaluation and Refinement in End-to-End Autonomous Driving"
authors: ["Yuhao Wei", "Yong Chen", "Chen Yang", "Yingchen Wang", "Delin Ouyang", "Lingfeng Qi", "Qi Lan", "Zhanhua Zhang", "Jie Li", "Guofa Li"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.13409"
doi: "10.48550/arXiv.2610.13409"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-13
---

# ManeuverFlow: Maneuver Hypothesis Generation with Future Evidence for Trajectory Evaluation and Refinement in End-to-End Autonomous Driving

> Yuhao Wei, Yong Chen, Chen Yang, Yingchen Wang, Delin Ouyang, Lingfeng Qi, Qi Lan, Zhanhua Zhang, Jie Li, Guofa Li · 2026
> [arXiv](https://arxiv.org/abs/2610.13409) · [PDF](https://arxiv.org/pdf/2610.13409)

## Abstract

End-to-end planning in complex scenes must model diverse driving intentions and select the most appropriate trajectory using scene context and future risks. However, multi-query regression may collapse to one mode, while anchor-based and generative planners share a scaling bottleneck: small candidate sets limit maneuver coverage or discovery of high-quality trajectories, whereas large sets increase generation and scoring costs. We propose ManeuverFlow to generate trajectories for distinct intentions in one step and evaluate and refine them using current and future evidence. The model selects relevant maneuver modes, draws corresponding noise from the Gaussian mixture prior, and maps it to intention-specific trajectories through a maneuver-routed mixture-of-experts MeanFlow field. Current features and future features predicted by the world model are aggregated along each candidate path into trajectory-specific evidence for PDM-factor prediction. Using the same evidence, the refiner predicts local Frenet residuals for selected candidates; refined and retained candidates are then jointly re-scored for selection. With a lightweight TransFuser-style ResNet-34 backbone, ManeuverFlow achieves 90.6 PDMS and 90.1 EPDMS on NAVSIM v1/v2 navtest, respectively. On WorldEngine's recent 3DGS closed-loop benchmark, it attains the highest listed PDMS$^\ast$ scores of 75.19 and 74.58 under logged and IDM-controlled traffic, respectively. Code: https://github.com/wyh-autonomy/maneuverflow.

## TL;DR

End-to-end planning in complex scenes must model diverse driving intentions and select the most appropriate trajectory using scene context and future risks. However, multi-query regression may collapse to one mode, while anchor-based and generative planners share a scaling bottleneck: small candidate sets limit maneuver coverage or discovery of high-quality trajectories, whereas large sets increase generation and scoring costs.

## Related
<!-- [[other-paper-citekey]] -->
