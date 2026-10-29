---
citekey: "yoonAskBeforeItTellsBenchmarkBodyCueTransfer2026"
title: "Ask Before It Tells: Benchmark-to-Robot Body-Cue Transfer for a Question-First Bedside Robot"
authors: ["Dongsik Yoon"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.24099"
doi: "10.48550/arXiv.2609.24099"
tags: [paper, embodied-ai, "cs.HC", "cs.RO"]
status: unread
rating:
created: 2026-09-23
---

# Ask Before It Tells: Benchmark-to-Robot Body-Cue Transfer for a Question-First Bedside Robot

> Dongsik Yoon · 2026
> [arXiv](https://arxiv.org/abs/2609.24099) · [PDF](https://arxiv.org/pdf/2609.24099)

## Abstract

Body-cue recognition can support assistive robots, but benchmark accuracy does not guarantee reliable behavior under a robot-camera viewpoint. We present Nuni, a bedside robot prototype that treats a detected distress cue as a reason to ask rather than a reason to alert. We compare two X3D-UGT RGB appearance classifiers, which reach 97.7% and 94.8% six-way accuracy on NTU RGB+D, with a pose-centric hybrid pipeline on 28 single-actor scripted clips recorded from the robot camera. The hybrid path achieved 0.71 six-way macro recall, versus 0.25 and 0.29 for the fine-tuned and from-scratch RGB variants. More importantly for interaction, it produced a question-triggering distress cue in 12/16 distress clips and would have prompted unnecessarily in 2/8 normal clips; the RGB variants yielded a question-triggering cue in only 2/16 and 3/16 distress clips. We separately tested the question-first controller through event injection. All 13 state-transition trials passed: valid responses caused stand-down, two unanswered prompts produced one alert, and three boundary conditions were handled correctly. These results are a preliminary technical evaluation, not a user study or medical validation, but they show how interaction policy can limit the consequences of uncertain perception.

## TL;DR

Body-cue recognition can support assistive robots, but benchmark accuracy does not guarantee reliable behavior under a robot-camera viewpoint. We present Nuni, a bedside robot prototype that treats a detected distress cue as a reason to ask rather than a reason to alert.

## Related
<!-- [[other-paper-citekey]] -->
