---
citekey: "leeRapidLearningDynamicManipulationSkillsJuggling2026"
title: "Rapid On-Robot Learning for Dynamic Manipulation Skills: Robot Juggling"
authors: ["Taeyoon Lee", "Chunpeng Wang", "Christopher G. Atkeson", "Alfred A. Rizzi", "Nicolas Rojas"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2608.26800"
doi: "10.48550/arXiv.2608.26800"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-08
---

# Rapid On-Robot Learning for Dynamic Manipulation Skills: Robot Juggling

> Taeyoon Lee, Chunpeng Wang, Christopher G. Atkeson, Alfred A. Rizzi, Nicolas Rojas · 2026
> [arXiv](https://arxiv.org/abs/2608.26800) · [PDF](https://arxiv.org/pdf/2608.26800)

## Abstract

We present an online learning framework that enables a bimanual robot to acquire diverse juggling patterns directly on physical hardware within minutes, even with a significant sim2real gap. One of the most important lessons from this work is that a model, even when far from reality, can be extremely useful for learning. This motivates a central philosophy of our approach: learning should build upon the robot's current knowledge rather than replace it. Our regularized memory-based learning puts this principle into practice by learning a local model from accumulated experience while retaining the global prior model to extrapolate where experience is sparse. This enables efficient and stable online learning from each new experience without resorting to uninformed exploration over a vast space of possible behaviors. Equally important to continual on-robot learning is safety, allowing the robot to repeatedly practice and improve in the real world. We construct a mutually reachable set that allows safe transitions between successive throws and catches, without driving either arm into a state from which its next action would require violating the robot's joint or actuator limits. Together, these ideas enable a bimanual robot with multi-fingered hands and onboard vision to safely learn and compose five canonical three-ball juggling patterns, including cascade, tennis, half-shower, shower, and box, within less than 5 minutes of real-world interaction. More broadly, this work points toward robots that build upon imperfect prior knowledge and continually refine their behavior through their own real-world experience.

## TL;DR

We present an online learning framework that enables a bimanual robot to acquire diverse juggling patterns directly on physical hardware within minutes, even with a significant sim2real gap. One of the most important lessons from this work is that a model, even when far from reality, can be extremely useful for learning.

## Related
<!-- [[other-paper-citekey]] -->
