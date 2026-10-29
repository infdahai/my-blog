---
citekey: "samuelsonOpenSet3DSceneGraphsFieldRoboticsOutdoor2026"
title: "Open-Set 3D Scene Graphs for Field Robotics: An Outdoor Case Study"
authors: ["Chad R. Samuelson", "Gabriel R. Slade", "Joshua G. Mangelson"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.04607"
doi: "10.48550/arXiv.2609.04607"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-07
---

# Open-Set 3D Scene Graphs for Field Robotics: An Outdoor Case Study

> Chad R. Samuelson, Gabriel R. Slade, Joshua G. Mangelson · 2026
> [arXiv](https://arxiv.org/abs/2609.04607) · [PDF](https://arxiv.org/pdf/2609.04607)

## Abstract

Three-dimensional scene graphs (3DSGs) have emerged as a promising approach for building geometrically grounded, semantically informed, hierarchical general-purpose maps to support high-level robotic reasoning. However, the behavior of 3DSGs in real-world outdoor deployments remains poorly understood, particularly when combined with open-set vision-language models (VLMs). In this field report, we analyze the components common to most 3DSG representations across five outdoor robotic datasets to characterize challenges that arise in complex outdoor environments. Using the recently proposed Terra 3DSG as a case study, we investigate semantic point embeddings, place-node graph navigation, region-level understanding, and memory size across the five diverse datasets. We additionally introduce novel consistency metrics to evaluate whether semantic and structural graph properties remain stable across repeated traversals of the same environment. Our analysis reveals that outliers and multiple modes are common in VLM point embeddings across all tested datasets with outlier ratios above $0.1$ for around $30\%$ of points. We demonstrate the feasibility of outdoor 3DSGs for navigation-based object retrieval, achieving success rates near $70\%$, though performance is limited by traversability failures and inefficient routing, with trajectories averaging approximately $66\%$ suboptimal path efficiency. Region-level understanding remains challenging in complex natural environments, with low average F1 scores around $0.359$. Overall, our results show that outdoor 3DSGs can maintain compact (less than $600$MB for multi-kilometer trajectories) and relatively consistent large-scale environment representations, while highlighting open challenges in handling multiple semantic modes, incorporating traversability into graph structures, and improving higher-level region understanding.

## TL;DR

Three-dimensional scene graphs (3DSGs) have emerged as a promising approach for building geometrically grounded, semantically informed, hierarchical general-purpose maps to support high-level robotic reasoning. However, the behavior of 3DSGs in real-world outdoor deployments remains poorly understood, particularly when combined with open-set vision-language models (VLMs).

## Related
<!-- [[other-paper-citekey]] -->
