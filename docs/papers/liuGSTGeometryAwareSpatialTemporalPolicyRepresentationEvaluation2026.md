---
citekey: "liuGSTGeometryAwareSpatialTemporalPolicyRepresentationEvaluation2026"
title: "Robot-GST: geometry-aware spatial-temporal robot policy representation and evaluation"
authors: ["Sichao Liu", "Zekun Wang", "Lixuan Tang", "Yiming Li", "Xiaohan Wang", "Hanzhi Zhang", "Daqiang Guo", "Peng Zhou", "Lihui Wang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.33872"
doi: "10.48550/arXiv.2609.33872"
tags: [paper, embodied-ai, "cs.AI", "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# Robot-GST: geometry-aware spatial-temporal robot policy representation and evaluation

> Sichao Liu, Zekun Wang, Lixuan Tang, Yiming Li, Xiaohan Wang, Hanzhi Zhang, Daqiang Guo, Peng Zhou, Lihui Wang · 2026
> [arXiv](https://arxiv.org/abs/2609.33872) · [PDF](https://arxiv.org/pdf/2609.33872)

## Abstract

Robotic manipulation policies are advancing rapidly with increasing reliance on vision-language models for end-to-end decision making. However, reliable deployment remains challenging because many policies lack explicit mechanisms for predicting task outcomes and evaluating whether generated actions will achieve desired final states, causing execution errors to accumulate during long-horizon manipulation. We present Robot-GST, a geometry-aware spatio-temporal behaviour representation and evaluation framework that constructs a Gaussian-SAM robotic environment for real-to-sim policy verification and improves the reliability of real-world manipulation deployment. Our approach constructs a high-fidelity robotic environment from RGB-D observations using 3D Gaussian Splatting and SAM3D, enabling ``simulation and evaluation before acting''. It integrates visual observations and language instructions with spatio-temporal reasoning for long-horizon task planning using large vision-language models. To bridge high-level planning and real-world execution, we introduce Gaussian-aware final-state estimation through geometric sampling and state-based trajectory planning. Before execution, candidate action sequences are simulated and evaluated in the Gaussian-SAM environment to filter infeasible behaviours. We validate our approach on representative manipulation tasks involving rigid, soft, and deformable objects, including cube placing, toy packing, and duck rearrangement, demonstrating that geometry-aware spatio-temporal reasoning and state-aware execution improve manipulation reliability across different object categories. Our results suggest that combining geometry-aware reconstruction with high-quality rendering and simulation provides a scalable approach for evaluating robotic manipulation behaviours. Website: https://robot-gst.github.io

## TL;DR

Robotic manipulation policies are advancing rapidly with increasing reliance on vision-language models for end-to-end decision making. However, reliable deployment remains challenging because many policies lack explicit mechanisms for predicting task outcomes and evaluating whether generated actions will achieve desired final states, causing execution errors to accumulate during long-horizon manipulation.

## Related
<!-- [[other-paper-citekey]] -->
