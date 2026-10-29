---
citekey: "satoDREAMDeploymentTimeDemonstrationGenerationRealSimScalable2026"
title: "DREAM: Deployment-Time Demonstration Generation via Real-to-Sim for Scalable Policy Adaptation"
authors: ["Makoto Sato", "Tatsuya Matsushima", "Yutaka Matsuo", "Yusuke Iwasawa"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.29078"
doi: "10.48550/arXiv.2608.29078"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-02
---

# DREAM: Deployment-Time Demonstration Generation via Real-to-Sim for Scalable Policy Adaptation

> Makoto Sato, Tatsuya Matsushima, Yutaka Matsuo, Yusuke Iwasawa · 2026
> [arXiv](https://arxiv.org/abs/2608.29078) · [PDF](https://arxiv.org/pdf/2608.29078)

## Abstract

Vision-language-action (VLA) models have made strong progress in language-conditioned robot manipulation, but improving their performance in a new workspace still often requires action-labeled data from that environment. Collecting such data by human teleoperation is costly, especially when each workspace, object arrangement, or task may require new demonstrations. We present DREAM, a framework that generates fine-tuning data for a pretrained VLA from a captured workspace and a language instruction, without requiring a task-specific human demonstration. DREAM reconstructs the workspace, automatically translates the instruction into symbolic task goals and success criteria using a large language model, and uses task-and-motion planning to generate feasible robot trajectories. The planned trajectories are augmented across randomized object configurations, verified by the generated success criteria, and rendered into image-action examples for VLA fine-tuning. Through real-robot experiments on language-conditioned manipulation tasks, we study whether DREAM can serve as a scalable data-collection system for the deployment workspace by examining whether fine-tuning on its automatically generated data improves success over direct deployment and how its data-collection cost compares with human teleoperation when adapting a VLA to a new workspace.

## TL;DR

Vision-language-action (VLA) models have made strong progress in language-conditioned robot manipulation, but improving their performance in a new workspace still often requires action-labeled data from that environment. Collecting such data by human teleoperation is costly, especially when each workspace, object arrangement, or task may require new demonstrations.

## Related
<!-- [[other-paper-citekey]] -->
