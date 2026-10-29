---
citekey: "laiComManipOverfittingManipulationPoliciesComfortableRegions2026"
title: "ComManip: Overfitting Manipulation Policies to Comfortable Regions"
authors: ["Yidan Lai", "Xinyi Chen", "Shuquan Man", "Huiping Zhuang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.36928"
doi: "10.48550/arXiv.2609.36928"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# ComManip: Overfitting Manipulation Policies to Comfortable Regions

> Yidan Lai, Xinyi Chen, Shuquan Man, Huiping Zhuang · 2026
> [arXiv](https://arxiv.org/abs/2609.36928) · [PDF](https://arxiv.org/pdf/2609.36928)

## Abstract

Training robot manipulation policies relies on costly robot demonstrations, making large-scale data collection impractical. Meanwhile, to improve policy generalization, existing approaches seek greater diversity in visual observations by varying object placements, viewpoints, and robot configurations during data collection. However, under a limited demonstration budget, this strategy forces the policy to model diverse visual observations, providing insufficient supervision to learn reliable observation-action correspondences under similar local conditions. Our study reveals that policies trained under this strategy achieve lower task success rates than those trained within a compact, visually and kinematically stable region. We refer to these stable regions as comfortable manipulation regions. To exploit this finding, we propose ComManip, a learning paradigm that specializes manipulation policies to comfortable manipulation regions. During inference, ComManip repositions the mobile base until the detected target center enters the familiar image-space range estimated from comfortable-region demonstrations. It then executes the same manipulation policy, enabling effective manipulation across diverse target locations. We conduct extensive experiments across multiple manipulation tasks, demonstration budgets, and policy families including ACT, $π_{0.5}$, RDT, OpenVLA-OFT, and SmolVLA. The results demonstrate that ComManip improves task success by roughly 20 percentage points or more across different policy architectures in large workspaces under limited demonstration budgets, suggesting that specializing manipulation policies to comfortable regions provides a more data-efficient learning paradigm for manipulation.

## TL;DR

Training robot manipulation policies relies on costly robot demonstrations, making large-scale data collection impractical. Meanwhile, to improve policy generalization, existing approaches seek greater diversity in visual observations by varying object placements, viewpoints, and robot configurations during data collection.

## Related
<!-- [[other-paper-citekey]] -->
