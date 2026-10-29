---
citekey: "huColoACTMultiCueActionChunkingSmoothAutonomousColon2026"
title: "ColoACT: Multi-Cue Action Chunking for Smooth Autonomous Colon Navigation on a Self-Propelled Endoscopic Robot"
authors: ["Jian Hu", "Shujing He", "Leixin Chang", "Zongze Li", "Ding Huang", "Chaoyang Shi", "Chengzhi Hu"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.01258"
doi: "10.48550/arXiv.2610.01258"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# ColoACT: Multi-Cue Action Chunking for Smooth Autonomous Colon Navigation on a Self-Propelled Endoscopic Robot

> Jian Hu, Shujing He, Leixin Chang, Zongze Li, Ding Huang, Chaoyang Shi, Chengzhi Hu · 2026
> [arXiv](https://arxiv.org/abs/2610.01258) · [PDF](https://arxiv.org/pdf/2610.01258)

## Abstract

Autonomous colonoscopic navigation can reduce operator burden and the risk of loop formation or tissue trauma, but remains challenging due to deformable anatomy, weak-texture and specular endoscopic visuals, and contact-rich viscoelastic interactions. Existing methods either rely on geometry-driven pipelines, which are efficient and interpretable yet brittle due to manually engineered features and switching logic, or adopt learning-based policies, whose inferred depth/geometry can become temporally inconsistent or overly smooth under weak texture and specular highlights while simulation-trained variants (e.g., deep reinforcement learning) may further suffer from a sim-to-real gap. We propose ColoACT, an autonomous navigation system that integrates an RGB-D-E based Action Chunking Transformer policy (ColoACT policy) for a compact self-propelled Bevel-Gear-Based Endoscopic Robot (BGER). The ColoACT policy augments RGB with estimated relative depth and a gradient-based pseudo-elevation map to enhance fold-ridge saliency and other high-frequency geometric cues, and enables smooth continuous control of the BGER by predicting overlapping action chunks and fusing them via temporal ensembling. In different \textit{ex-vivo} porcine colons (approximately 60 cm), our system achieves success rates of 85.4\% and 72.5\% in straight and curved segments, respectively, and achieves 70\% success in 90-degree turns and 60\% in double-bend sequences, with feasibility further demonstrated in challenging triple-bend segments. The project page is available at: https://Adamhu1.github.io/ColoACT/.

## TL;DR

Autonomous colonoscopic navigation can reduce operator burden and the risk of loop formation or tissue trauma, but remains challenging due to deformable anatomy, weak-texture and specular endoscopic visuals, and contact-rich viscoelastic interactions. Existing methods either rely on geometry-driven pipelines, which are efficient and interpretable yet brittle due to manually engineered features and switching logic, or adopt learning-based policies, whose inferred depth/geometry can become temporally inconsistent or overly smooth under weak texture and specular highlights while...

## Related
<!-- [[other-paper-citekey]] -->
