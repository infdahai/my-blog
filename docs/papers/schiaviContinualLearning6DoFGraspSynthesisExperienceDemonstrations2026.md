---
citekey: "schiaviContinualLearning6DoFGraspSynthesisExperienceDemonstrations2026"
title: "Continual Learning for 6-DoF Grasp Synthesis via Experience and Demonstrations"
authors: ["Giulio Schiavi", "Andrei Cramariuc", "Michael Pantic", "Roland Siegwart"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.01301"
doi: "10.48550/arXiv.2610.01301"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# Continual Learning for 6-DoF Grasp Synthesis via Experience and Demonstrations

> Giulio Schiavi, Andrei Cramariuc, Michael Pantic, Roland Siegwart · 2026
> [arXiv](https://arxiv.org/abs/2610.01301) · [PDF](https://arxiv.org/pdf/2610.01301)

## Abstract

Most current grasp synthesis systems are trained offline and remain fixed during deployment. While this works well when deployment conditions resemble the training data, performance can degrade when robots encounter conditions they have not seen before, such as unfamiliar objects. In this work, we present a continual-learning framework for single-view 6-DoF grasp synthesis for a parallel-jaw gripper in cluttered scenes. Rather than finetuning a large parametric model, our method adapts through memory in a learned embedding space: grasp outcomes update future grasp scores, while optional user demonstrations are recalled and transferred to new scenes as additional candidate grasps. We evaluate our method in simulation and in extensive real-world experiments comprising over 1500 grasp trials. We show that our method matches the performance of existing 6-DoF grasping baselines even before adaptation, improves online on unseen objects from categories absent or underrepresented during training, and supports long-horizon continual learning with limited forgetting. In real-world experiments, our method reaches over 90\% success rates on several challenging object categories after only 50 online grasp attempts. Videos and code at https://giuschio.github.io/cl_grasping/.

## TL;DR

Most current grasp synthesis systems are trained offline and remain fixed during deployment. While this works well when deployment conditions resemble the training data, performance can degrade when robots encounter conditions they have not seen before, such as unfamiliar objects.

## Related
<!-- [[other-paper-citekey]] -->
