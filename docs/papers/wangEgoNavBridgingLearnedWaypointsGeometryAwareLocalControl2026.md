---
citekey: "wangEgoNavBridgingLearnedWaypointsGeometryAwareLocalControl2026"
title: "EgoNav: Bridging Learned Waypoints and Geometry-Aware Local Control for Robust Indoor Navigation"
authors: ["Jing Wang", "Shiqi Zhao", "Hairong Qu", "Peng Yin"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.25642"
doi: "10.48550/arXiv.2608.25642"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# EgoNav: Bridging Learned Waypoints and Geometry-Aware Local Control for Robust Indoor Navigation

> Jing Wang, Shiqi Zhao, Hairong Qu, Peng Yin · 2026
> [arXiv](https://arxiv.org/abs/2608.25642) · [PDF](https://arxiv.org/pdf/2608.25642)

## Abstract

Image-goal navigation using lightweight topological maps is a practical paradigm for indoor robot deployment: the map requires only geotagged images, and localization relies on visual matching rather than precise pose estimation. However, learned waypoint predictors can produce targets that violate geometric constraints or deviate from the global path. Executing these waypoints safely further requires a local planner capable of collision avoidance, yet existing systems either lack one or rely on fixed parameters that cannot adapt to confined spaces. To address these limitations while retaining the navigational intuition of the learned predictor, we present EgoNav, a hierarchical system that implements this idea by generating candidates from semantically segmented traversable regions and scoring them alongside the learned waypoint for geometric safety, directional coherence, and fidelity to the learned prior. An adaptive local path planner then executes the refined waypoint with parameters modulated based on the refinement outcome. Experiments in Habitat-sim and on a physical humanoid robot show that EgoNav consistently outperforms contemporary baselines in both success rate and path efficiency.

## TL;DR

Image-goal navigation using lightweight topological maps is a practical paradigm for indoor robot deployment: the map requires only geotagged images, and localization relies on visual matching rather than precise pose estimation. However, learned waypoint predictors can produce targets that violate geometric constraints or deviate from the global path.

## Related
<!-- [[other-paper-citekey]] -->
