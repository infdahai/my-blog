---
citekey: "huangHumynexSurg1CuratedExpertLiposuctionDataset2026"
title: "HumynexSurg-1: A Curated Expert Liposuction Dataset"
authors: ["Rhea Huang", "David L. Matlock", "Laurence Reich"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.23885"
doi: "10.48550/arXiv.2609.23885"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-09-23
---

# HumynexSurg-1: A Curated Expert Liposuction Dataset

> Rhea Huang, David L. Matlock, Laurence Reich · 2026
> [arXiv](https://arxiv.org/abs/2609.23885) · [PDF](https://arxiv.org/pdf/2609.23885)

## Abstract

Robot foundation models learn manipulation from large demonstration corpora, but surgery is missing from those corpora: across the 780-hour Open-H surgical collection, one dataset carries synchronized force and none covers an aesthetic procedure. Liposuction is the hard case, because the instrument works under the skin and the surgeon operates by feel and by judgment. Humynex Robotics builds curated expert datasets for this kind of procedure. HumynexSurg-1 is the first release: a master liposuction surgeon performing on porcine abdominal tissue while narrating every decision, recorded with synchronized suction pressure, six-axis hand force/torque, top-down RGB-D video, side video and a lavalier microphone -- 14 episodes, 42,738 frames, 35.6 minutes, 356 utterances of which 95% compile into a liposuction-specific label schema. The capture follows a patent-pending sensing plan organized around the quantities a policy needs, so a channel captured today by a model can be upgraded to a sensor tomorrow without changing the data format. This release captures the instrument motion as a tool-hand track in the side video and provides the force channel as state; the funded capture adds a measured 6-DoF handle pose, a validated force channel, ultrasound imaging of the fat layer, and palpation sensing. As a proof of concept, NVIDIA Isaac GR00T N1.7 fine-tunes on the dataset with no custom code in under an hour per run and learns the recorded sessions; scaling probes on the same episodes show where further gains come from: every new session lowers the error on an unseen session. The dataset, its label schema, its quality-assurance reports and its evaluation protocol are the product; the next capture, many short sessions across fat regions with the sensors named here, is what the probes point to.

## TL;DR

Robot foundation models learn manipulation from large demonstration corpora, but surgery is missing from those corpora: across the 780-hour Open-H surgical collection, one dataset carries synchronized force and none covers an aesthetic procedure. Liposuction is the hard case, because the instrument works under the skin and the surgeon operates by feel and by judgment.

## Related
<!-- [[other-paper-citekey]] -->
