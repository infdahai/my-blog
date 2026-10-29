---
citekey: "johnsonRefineWhereItMattersContactAdaptiveMeshingDeformable2026"
title: "Refine Where It Matters: Contact-Adaptive Meshing for Deformable Object Manipulation"
authors: ["Gabriel Johnson", "Tom Olesch", "Fei Liu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.14142"
doi: "10.48550/arXiv.2610.14142"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-16
---

# Refine Where It Matters: Contact-Adaptive Meshing for Deformable Object Manipulation

> Gabriel Johnson, Tom Olesch, Fei Liu · 2026
> [arXiv](https://arxiv.org/abs/2610.14142) · [PDF](https://arxiv.org/pdf/2610.14142)

## Abstract

Deformable-object manipulation requires accurate modeling of highly localized contact while maintaining simulation speeds suitable for interactive use. Uniformly fine tetrahedral meshes can resolve these interactions, but they introduce unnecessary degrees of freedom throughout the object. Coarse meshes are more efficient, yet they may under-resolve contact-induced deformation. We present a contact-adaptive mesh refinement framework that introduces spatial resolution only where it is most useful. The method uses geometric, elastic, and contact quantities already available from the deformable-body solver to score candidate edges. A fully GPU-parallel procedure then selects a conflict-free subset and updates both mesh topology and physical state directly within the simulation loop. We evaluate the approach on real deformable-object manipulation sequences. Adaptive refinement reduces simulation-to-real error, improves agreement with a fine-mesh reference, and remains substantially more efficient than uniformly fine simulation. These results show that local refinement can improve physical fidelity without incurring the cost of a globally fine discretization. The framework provides a practical basis for contact-rich simulation in interactive manipulation, sim-to-real modeling, and online physical digital twins.

## TL;DR

Deformable-object manipulation requires accurate modeling of highly localized contact while maintaining simulation speeds suitable for interactive use. Uniformly fine tetrahedral meshes can resolve these interactions, but they introduce unnecessary degrees of freedom throughout the object.

## Related
<!-- [[other-paper-citekey]] -->
