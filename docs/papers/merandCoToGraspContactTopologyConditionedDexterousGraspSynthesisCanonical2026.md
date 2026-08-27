---
citekey: "merandCoToGraspContactTopologyConditionedDexterousGraspSynthesisCanonical2026"
title: "CoToGrasp: Contact-Topology-Conditioned Dexterous Grasp Synthesis via Canonical Workspace Learning"
authors: ["Julien Merand", "Boris Meden", "Liming Chen", "Mathieu Grossard"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.19776"
doi: "10.48550/arXiv.2608.19776"
tags: [paper, embodied-ai, "cs.AI", "cs.RO"]
status: unread
rating:
created: 2026-08-27
---

# CoToGrasp: Contact-Topology-Conditioned Dexterous Grasp Synthesis via Canonical Workspace Learning

> Julien Merand, Boris Meden, Liming Chen, Mathieu Grossard · 2026
> [arXiv](https://arxiv.org/abs/2608.19776) · [PDF](https://arxiv.org/pdf/2608.19776)

## Abstract

Current dexterous grasp planners primarily optimize for physical stability, focusing on whether an object can be grasped rather than how it should be grasped to support downstream functional tasks. However, conditioning grasp synthesis on specific human grasp taxonomies typically requires prohibitively expensive, object-annotated datasets. To address these limitations, we propose CoToGrasp, a novel generative framework that synthesizes diverse, stable grasps strictly conditioned on specific contact topologies. To bypass the data collection bottleneck, CoToGrasp is trained entirely in an object-agnostic manner. We introduce a feature-based canonical workspace that projects local object features into a unified gripper-centric domain, effectively decoupling the semantic functional intent from the arbitrary object geometry. By learning the intrinsic contact manifold of the gripper within this workspace, our model achieves zero-shot generalization to unseen objects at inference. Extensive evaluations on the large-scale DexGraspNet dataset demonstrate that CoToGrasp achieves state-of-the-art performance, outperforming existing taxonomy-guided planners. Finally, we demonstrate the physical viability and kinematic feasibility of our synthesized contact topologies on a physical robot platform. Code is available on our project website at https://cea-list.github.io/cotograspweb/ .

## TL;DR

Current dexterous grasp planners primarily optimize for physical stability, focusing on whether an object can be grasped rather than how it should be grasped to support downstream functional tasks. However, conditioning grasp synthesis on specific human grasp taxonomies typically requires prohibitively expensive, object-annotated datasets.

## Related
<!-- [[other-paper-citekey]] -->
