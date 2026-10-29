---
citekey: "wuRoboSTDZeroShotSingleDualTransferSagittalMirroring2026"
title: "RoboSTD: Zero-Shot Single-to-Dual Transfer via Sagittal Mirroring for Bimanual Learning"
authors: ["Hongyu Wu", "Chong Liu", "Shaoxuan Xie", "Shaqi Luo", "Hanyu Feng", "Shihan Wu", "Guocai Yao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.36685"
doi: "10.48550/arXiv.2610.36685"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-29
---

# RoboSTD: Zero-Shot Single-to-Dual Transfer via Sagittal Mirroring for Bimanual Learning

> Hongyu Wu, Chong Liu, Shaoxuan Xie, Shaqi Luo, Hanyu Feng, Shihan Wu, Guocai Yao · 2026
> [arXiv](https://arxiv.org/abs/2610.36685) · [PDF](https://arxiv.org/pdf/2610.36685)

## Abstract

Bimanual robot manipulation plays an important role in real-world robotic applications, but the high cost of collecting bimanual demonstrations limits the scalable development of bimanual policy learning. Meanwhile, existing single-arm manipulation data are difficult to directly transfer to bimanual systems due to the Single-to-Dual gap in action spaces, coordination requirements, and arm-side spatial preference. To address this issue, we propose RoboSTD, a zero-shot Single-to-Dual data construction method for bimanual robot learning. RoboSTD first applies sagittal-plane mirroring to observations, proprioception, and actions to construct executable contralateral pseudo-demonstrations. It then uses an LLM to generate structured spatio-temporal coordination constraints that guide the reconstruction of pseudo-bimanual supervision across workspace regions and task stages. We evaluate RoboSTD on the AgileX ALOHA platform in both RoboTwin simulation and real-world settings. Experiments demonstrate the effectiveness of RoboSTD for bimanual policy learning. Without requiring additional bimanual demonstrations, RoboSTD increases the average number of collected cups to 2.11x that of the single-arm baseline in the cup collection task. Project page: https://huahungy.github.io/RoboSTD/

## TL;DR

Bimanual robot manipulation plays an important role in real-world robotic applications, but the high cost of collecting bimanual demonstrations limits the scalable development of bimanual policy learning. Meanwhile, existing single-arm manipulation data are difficult to directly transfer to bimanual systems due to the Single-to-Dual gap in action spaces, coordination requirements, and arm-side spatial preference.

## Related
<!-- [[other-paper-citekey]] -->
