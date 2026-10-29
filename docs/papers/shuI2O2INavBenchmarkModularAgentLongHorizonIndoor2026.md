---
citekey: "shuI2O2INavBenchmarkModularAgentLongHorizonIndoor2026"
title: "I2O2I-Nav: A Benchmark with a Modular Agent for Long-Horizon Indoor-to-Outdoor-to-Indoor Navigation"
authors: ["Zhengjie Shu", "Wanyu Li", "Di Xiao", "Lingxin Jiang", "Lai Jiang", "Kaidi Hu", "Xincheng Tang", "Wenkang Hu", "Haoran Wang", "Jinchuan Zhang", "Chang Chen", "Wei Li", "Jia Pan", "Ruigang Yang"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.18307"
doi: "10.48550/arXiv.2610.18307"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-18
---

# I2O2I-Nav: A Benchmark with a Modular Agent for Long-Horizon Indoor-to-Outdoor-to-Indoor Navigation

> Zhengjie Shu, Wanyu Li, Di Xiao, Lingxin Jiang, Lai Jiang, Kaidi Hu, Xincheng Tang, Wenkang Hu, Haoran Wang, Jinchuan Zhang, Chang Chen, Wei Li, Jia Pan, Ruigang Yang · 2026
> [arXiv](https://arxiv.org/abs/2610.18307) · [PDF](https://arxiv.org/pdf/2610.18307)

## Abstract

Service and delivery robots often need to complete long-horizon navigation missions spanning indoor and outdoor environments. Existing embodied navigation benchmarks primarily evaluate isolated stages or partial cross-domain journeys, providing limited support for assessing how heterogeneous navigation capabilities compose under continuous execution. We introduce I2O2I-Nav, a physics-enabled benchmark of 20 real-world composite scenes spanning over 115,000 square meters across multiple buildings and floors, with aligned 3DGS rendering and collision geometry. Its three-level evaluation progresses from independent primitives to two-stage compositions and complete four-stage I2O2I missions. Each stage starts from its predecessor's actual endpoint, while stage-conditional metrics track completion and localize failures along the mission. We further propose the MODULAR-Agent that coordinates frozen navigation policies through completion verification, stage handoffs, and bounded recovery. Evaluation across 1,374 episodes highlights the difficulty of continuous composition. The MODULAR-Agent achieves 40.5-76% success on individual primitives, but full I2O2I success remains low. Compared with a fixed policy chain using the same underlying policies, it more than doubles success on both Indoor-to-Outdoor (I2O) and Outdoor-to-Indoor (O2I), while improving full-mission success from 1.15% to 4.02%. Stage-wise analysis shows that the MODULAR-Agent enables more missions to reach the final object-navigation stage, where conditional success remains low, revealing challenges in both long-horizon stage execution and completion decisions.

## TL;DR

Service and delivery robots often need to complete long-horizon navigation missions spanning indoor and outdoor environments. Existing embodied navigation benchmarks primarily evaluate isolated stages or partial cross-domain journeys, providing limited support for assessing how heterogeneous navigation capabilities compose under continuous execution.

## Related
<!-- [[other-paper-citekey]] -->
