---
citekey: "hechtlWrenchACTEnhancingPoliciesContactRichBehaviorDirect2026"
title: "Wrench-ACT: Enhancing Robot Policies for Contact Rich Behavior Using Direct Wrench Control"
authors: ["Johannes Hechtl", "Yannik Blei", "Simon Ball", "Reihaneh Mirjalili", "Michael Krawez", "Seongjin Bien", "Philipp Schmitt", "Wolfram Burgard"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.37552"
doi: "10.48550/arXiv.2609.37552"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-04
---

# Wrench-ACT: Enhancing Robot Policies for Contact Rich Behavior Using Direct Wrench Control

> Johannes Hechtl, Yannik Blei, Simon Ball, Reihaneh Mirjalili, Michael Krawez, Seongjin Bien, Philipp Schmitt, Wolfram Burgard · 2026
> [arXiv](https://arxiv.org/abs/2609.37552) · [PDF](https://arxiv.org/pdf/2609.37552)

## Abstract

While contact-rich manipulation requires deliberate regulation of interaction forces, recent approaches to robot manipulation learning predominantly represent actions as target positions or poses. Even methods that incorporate force sensing either use it solely as an observation or, when predicting forces as part of the output, rely on a hybrid force controller. In this paper, we propose an imitation learning policy that predicts wrenches as its sole action output for direct use by a pure force controller. Our studies suggest that force-domain imitation learning depends critically on data collection, with force-feedback teleoperation improving policy performance by capturing the operator's deliberate force regulation. Using Action Chunking with Transformers (ACT) as the base architecture, we train single-task models on bilateral wrench demonstrations and evaluate them on five contact-rich manipulation tasks. The wrench policy matches or outperforms position-based baselines across all tasks, with gains varying according to the degree of deliberate force regulation each task requires. Cross-condition ablations show that the bilateral data collection interface and the wrench action space each contribute independently to performance. To support further research, we will release over 1000 wrench-action demonstrations spanning these tasks on a companion website upon publication.

## TL;DR

While contact-rich manipulation requires deliberate regulation of interaction forces, recent approaches to robot manipulation learning predominantly represent actions as target positions or poses. Even methods that incorporate force sensing either use it solely as an observation or, when predicting forces as part of the output, rely on a hybrid force controller.

## Related
<!-- [[other-paper-citekey]] -->
