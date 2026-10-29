---
citekey: "pengHapticWorldInteractiveWorldSimulatorRealTimeTorqueFeedback2026"
title: "HapticWorld: an Interactive World Simulator with Real-time Torque Feedback"
authors: ["Shaoting Peng", "Litian Liang", "Yixuan Wang", "Ming Yang", "Katherine Driggs-Campbell", "Mark Cutkosky", "James Jingxi Xu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.31924"
doi: "10.48550/arXiv.2609.31924"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# HapticWorld: an Interactive World Simulator with Real-time Torque Feedback

> Shaoting Peng, Litian Liang, Yixuan Wang, Ming Yang, Katherine Driggs-Campbell, Mark Cutkosky, James Jingxi Xu · 2026
> [arXiv](https://arxiv.org/abs/2609.31924) · [PDF](https://arxiv.org/pdf/2609.31924)

## Abstract

Contact-rich manipulation depends on force sensing that is hard to infer from visual signals alone, both for collecting demonstrations and for training policies. Force-annotated data, however, remains hard to obtain at scale: real-robot collection ties every demonstration to physical hardware, physics simulators report contact forces that deviate systematically from real measurements, and learned world simulators, though scalable and realistic, are vision-only, so operators feel nothing during data collection and the data carries no force/torque (F/T) labels. We present HapticWorld, an interactive world simulator that predicts joint torque together with observations and renders it back to the operator in real time, closing the haptic loop between a human and a learned world model. Across three contact-rich tasks, torque feedback raises data collection throughput by 1.6 times on average. Policies trained on HapticWorld-generated demonstrations succeed in 54/60 real-world trials, approaching the 56/60 upper bound of real-world data, and far exceeding the 19/60 success rate of the vision-only baseline. Moreover, the success rates measured inside HapticWorld closely match real-world evaluation, demonstrating that HapticWorld can serve as a stand-alone F/T-conditioned policy evaluation platform.

## TL;DR

Contact-rich manipulation depends on force sensing that is hard to infer from visual signals alone, both for collecting demonstrations and for training policies. Force-annotated data, however, remains hard to obtain at scale: real-robot collection ties every demonstration to physical hardware, physics simulators report contact forces that deviate systematically from real measurements, and learned world simulators, though scalable and realistic, are vision-only, so operators feel nothing during data collection and the data carries no force/torque (F/T) labels.

## Related
<!-- [[other-paper-citekey]] -->
