---
citekey: "sharmaSpiderbotOpenSourceEnergyEfficientHexapodPassiveGravity2026"
title: "Spiderbot: An Open-Source Energy-Efficient Hexapod with Passive Gravity Compensation"
authors: ["Ritwik Sharma", "Vimarsh Shah", "Saransh Agrawal"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.26989"
doi: "10.48550/arXiv.2609.26989"
tags: [paper, embodied-ai, "cs.RO", "eess.SY"]
status: unread
rating:
created: 2026-09-26
---

# Spiderbot: An Open-Source Energy-Efficient Hexapod with Passive Gravity Compensation

> Ritwik Sharma, Vimarsh Shah, Saransh Agrawal · 2026
> [arXiv](https://arxiv.org/abs/2609.26989) · [PDF](https://arxiv.org/pdf/2609.26989)

## Abstract

Hexapod robots can achieve static stability with fewer actuated joints than bipeds or quadrupeds, yet many platforms still use 3-DOF legs, increasing weight and continuous torque requirement with limited gain in locomotion capability on flat, inclined and moderately rough terrains. We release Spiderbot, an open-source hexapod that uses a 4-bar linkage with a passive spring to mechanically support body weight, with a 2-DOF per-leg design that substantially reduces energy consumption. This mechanism substantially offloads gravitational torque during standing stance consuming only 1.5W (reduction of over 90\% over the unsprung version and up to 96\% over other similar hexapods). The passive spring compensation extends to payloads of up to 3.25kg with no additional torque requirements. The platform enables long-duration deployments on a modest battery budget and costs under \$400, making it suitable for large-scale multi-agent experiments. We validate the locomotion capabilities of the platform with an RL policy trained in mjlab, including successful sim-to-real transfer, despite the complexity of the mechanism. The platform is evaluated on flat and rough terrains, slope up to $15^\circ$ and step obstacles. We release all the CAD files, assembling instructions, and full training and deployment code along with the model checkpoints at https://erc-bpgc.github.io/SpiderBot/.

## TL;DR

Hexapod robots can achieve static stability with fewer actuated joints than bipeds or quadrupeds, yet many platforms still use 3-DOF legs, increasing weight and continuous torque requirement with limited gain in locomotion capability on flat, inclined and moderately rough terrains. We release Spiderbot, an open-source hexapod that uses a 4-bar linkage with a passive spring to mechanically support body weight, with a 2-DOF per-leg design that substantially reduces energy consumption.

## Related
<!-- [[other-paper-citekey]] -->
