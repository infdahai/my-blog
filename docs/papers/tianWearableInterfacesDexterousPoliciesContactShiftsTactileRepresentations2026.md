---
citekey: "tianWearableInterfacesDexterousPoliciesContactShiftsTactileRepresentations2026"
title: "From Wearable Interfaces to Dexterous Policies: Contact Shifts and Tactile Representations"
authors: ["Ruitong Tian", "Fang Xu", "Noah B. Wilson", "Xianyao Li", "Eric Jing Du"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.08870"
doi: "10.48550/arXiv.2610.08870"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-09
---

# From Wearable Interfaces to Dexterous Policies: Contact Shifts and Tactile Representations

> Ruitong Tian, Fang Xu, Noah B. Wilson, Xianyao Li, Eric Jing Du · 2026
> [arXiv](https://arxiv.org/abs/2610.08870) · [PDF](https://arxiv.org/pdf/2610.08870)

## Abstract

Unlike conventional teleoperation, wearable interfaces allow operators to collect dexterous demonstrations through their own hand motions while directly interacting with task objects. This direct interaction reduces dependence on the target robot during collection, but it also makes the collection hardware part of the physical process that generates each demonstration. Interface geometry can influence both how a task is performed and what tactile observations are recorded for learning. We study two versions of a DexUMI-family exoskeleton that share the same robot command definition, mapping procedure, and tactile module type but differ in hand-side geometry. The revised interface reduces reported physical demand, improves selected device ratings, enables tactile access in a precision grasp that is mechanically blocked by the baseline, and produces task-dependent changes in recorded contact. Lid twisting primarily exhibits a change in contact location, whereas egg carton opening primarily exhibits a change in contact occurrence. We then train matched policies using either a binary aggregate input or a spatial-plus-force input. On lid twisting and egg carton opening, policies trained on revised-interface demonstrations achieve higher success than those trained on baseline demonstrations, with a significant pooled interface effect. Across these and two additional tasks, USB insertion and soldering tool pick and place, the spatial-plus-force input likewise outperforms binary aggregation. These results show that wearable collection hardware is part of the data-generation process for robot learning. Such interfaces should therefore be evaluated not only through operator experience, but also through the tactile interactions they make recordable and the policy performance their demonstrations support.

## TL;DR

Unlike conventional teleoperation, wearable interfaces allow operators to collect dexterous demonstrations through their own hand motions while directly interacting with task objects. This direct interaction reduces dependence on the target robot during collection, but it also makes the collection hardware part of the physical process that generates each demonstration.

## Related
<!-- [[other-paper-citekey]] -->
