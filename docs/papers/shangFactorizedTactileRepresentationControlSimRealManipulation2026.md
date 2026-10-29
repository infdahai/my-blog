---
citekey: "shangFactorizedTactileRepresentationControlSimRealManipulation2026"
title: "Factorized Tactile Representation and Control for Sim-to-Real Manipulation"
authors: ["Siqi Shang", "Bianca Aumann", "Tye Brady", "Joshua Migdal", "Taskin Padir"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.10510"
doi: "10.48550/arXiv.2610.10510"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-09
---

# Factorized Tactile Representation and Control for Sim-to-Real Manipulation

> Siqi Shang, Bianca Aumann, Tye Brady, Joshua Migdal, Taskin Padir · 2026
> [arXiv](https://arxiv.org/abs/2610.10510) · [PDF](https://arxiv.org/pdf/2610.10510)

## Abstract

Tactile sim-to-real learning must bridge simulated contact and device-specific sensor responses while preserving information needed for control. We propose a factorized tactile representation and control framework that maps normal force and contact patch to an effective contact response recoverable from sensor readings. The response is separated into contact geometry, force distribution, and temporal contact change, with representation-specific encoding and randomization. A Tactile Gated Policy preserves these representations separately through control and operates over all mask configurations without retraining. We evaluate the approach through response reconstruction, spatial alignment, force regulation, and contact-rich adversarial peg insertion in simulation and the real world, enabling the utility and transfer reliability of different tactile representations to be assessed independently. The approach achieves <1 mm contact localization, 1.69 N force-tracking error on unseen geometries, and a 35% improvement in real-world adversarial peg insertion over the unfactorized response, with different tactile representations benefiting different interactions.

## TL;DR

Tactile sim-to-real learning must bridge simulated contact and device-specific sensor responses while preserving information needed for control. We propose a factorized tactile representation and control framework that maps normal force and contact patch to an effective contact response recoverable from sensor readings.

## Related
<!-- [[other-paper-citekey]] -->
