---
citekey: "tianExoBridgeLearningBareHandHandWornExoskeletonMapping2026"
title: "ExoBridge: Learning a Bare Hand to Hand-Worn Exoskeleton Mapping through Human Limb Coupling"
authors: ["Ruitong Tian", "Xianyao Li", "Noah B. Wilson", "Fang Xu", "Eric Jing Du"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.07692"
doi: "10.48550/arXiv.2610.07692"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-08
---

# ExoBridge: Learning a Bare Hand to Hand-Worn Exoskeleton Mapping through Human Limb Coupling

> Ruitong Tian, Xianyao Li, Noah B. Wilson, Fang Xu, Eric Jing Du · 2026
> [arXiv](https://arxiv.org/abs/2610.07692) · [PDF](https://arxiv.org/pdf/2610.07692)

## Abstract

Human video offers a scalable source of experience for dexterous robot learning, but obtaining motion and tactile supervision while preserving bare hand interaction remains challenging. We present ExoBridge, a framework that leverages human limb coupling to learn a bridging function from bare hand video to the motion and tactile state of a sensorized exoskeleton. Our central idea is to use coordinated bimanual behavior to connect an uninstrumented visual source with a measured manipulation interface. During collection, one hand remains bare and provides visual observations, while the opposite hand wears the exoskeleton and supplies synchronized motion and tactile measurements. These paired demonstrations train a temporal visual model to predict fingertip contact, continuous tactile intensity, and relative encoder motion from bare hand video alone. The exoskeleton defines an intermediate state space whose motion coordinates are linked to a dexterous robot hand through existing calibration. Evaluation on 1,215 demonstrations across four manipulation tasks uses held out collection sessions and yields a pooled any contact AUROC of 0.916 and a Pearson correlation of 0.790 for tactile intensity. The learned bridge also predicts relative changes in exoskeleton configuration from bare hand video. These results demonstrate that human limb coupling can turn exoskeleton measurements into supervision for bare hand video, establishing a learned bridge between human visual demonstrations and a robot oriented manipulation interface.

## TL;DR

Human video offers a scalable source of experience for dexterous robot learning, but obtaining motion and tactile supervision while preserving bare hand interaction remains challenging. We present ExoBridge, a framework that leverages human limb coupling to learn a bridging function from bare hand video to the motion and tactile state of a sensorized exoskeleton.

## Related
<!-- [[other-paper-citekey]] -->
