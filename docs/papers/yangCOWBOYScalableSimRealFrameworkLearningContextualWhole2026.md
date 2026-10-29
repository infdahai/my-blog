---
citekey: "yangCOWBOYScalableSimRealFrameworkLearningContextualWhole2026"
title: "COWBOY: A Scalable Sim-to-Real Framework for Learning Contextual Whole-Body Manipulation"
authors: ["Jiahui Yang", "Jason Jingzhou Liu", "Ray Muxin Liu", "Andrew E. Wang", "Kenneth Shaw", "Deepak Pathak", "Ruslan Salakhutdinov"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.28948"
doi: "10.48550/arXiv.2610.28948"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-22
---

# COWBOY: A Scalable Sim-to-Real Framework for Learning Contextual Whole-Body Manipulation

> Jiahui Yang, Jason Jingzhou Liu, Ray Muxin Liu, Andrew E. Wang, Kenneth Shaw, Deepak Pathak, Ruslan Salakhutdinov · 2026
> [arXiv](https://arxiv.org/abs/2610.28948) · [PDF](https://arxiv.org/pdf/2610.28948)

## Abstract

Mobile manipulators must adapt not only to objects, but also to the spatial context in which they appear: where to position the base, how to manipulate, and where to look while navigating surrounding scene geometry. To address this, we present COWBOY, a scalable sim-to-real framework for learning such contextual whole-body manipulation. On whole-body dexterous grasping, COWBOY transfers zero-shot to hundreds of objects and diverse in-the-wild scenes, spanning cluttered tabletops, shelves, drawers, and other unstructured settings. Rather than learning scene adaptation directly with RL in simulation, a vectorized environment-aware whole-body controller (WBC) handles reaching in thousands of scenes by coordinating base-arm motion, collision avoidance, and active vision. Then, local RL experts are trained in local scenes for object interaction and can be reused across thousands of full-scene layouts. We distill these composed WBC-RL teachers into a single vision policy that controls the mobile base, arm, dexterous hand, and actuated camera from point-cloud observations. The resulting policy exhibits contextual whole-body behavior, automatically adapting base placement, camera viewpoint, arm trajectory, and grasp strategy to observed scene and object geometry. Videos are available at https://cowboy-manip.com

## TL;DR

Mobile manipulators must adapt not only to objects, but also to the spatial context in which they appear: where to position the base, how to manipulate, and where to look while navigating surrounding scene geometry. To address this, we present COWBOY, a scalable sim-to-real framework for learning such contextual whole-body manipulation.

## Related
<!-- [[other-paper-citekey]] -->
