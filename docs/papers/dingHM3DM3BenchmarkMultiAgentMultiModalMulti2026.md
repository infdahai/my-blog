---
citekey: "dingHM3DM3BenchmarkMultiAgentMultiModalMulti2026"
title: "HM3D-M3: A Benchmark for Multi-Agent, Multi-Modal, Multi-Object Goal Navigation"
authors: ["Hongyu Ding", "Kanyu Xu", "Mingjia Chen", "Zixuan Chen", "Jieqi Shi", "Jing Huo", "Yifan Zhang", "Yang Gao"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.20121"
doi: "10.48550/arXiv.2610.20121"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-10-18
---

# HM3D-M3: A Benchmark for Multi-Agent, Multi-Modal, Multi-Object Goal Navigation

> Hongyu Ding, Kanyu Xu, Mingjia Chen, Zixuan Chen, Jieqi Shi, Jing Huo, Yifan Zhang, Yang Gao · 2026
> [arXiv](https://arxiv.org/abs/2610.20121) · [PDF](https://arxiv.org/pdf/2610.20121)

## Abstract

Rapid progress in AI agents and robotics makes it a matter of the near future that humans are served by a team of robots. Such a team will receive several goals at once, each specified in whatever form is convenient for the human, such as a category name, a photo, or a spoken description. Existing benchmarks study multi-agent, multi-modal, and multi-object goal navigation in isolation, and a benchmark that places all three in one episode is missing. To fill this gap, we introduce HM3D-M3. A team of K agents starts at distributed locations in a photorealistic indoor scene and searches for an unordered set of M object goals, each given as an open-vocabulary category, an instance image, or an instance description. HM3D-M3 provides 1,000 validation episodes over 3,926 goals from 379 open-vocabulary categories, 100K observation-assignment training samples, and two team-level metrics, goal-level SR and makespan-normalized SPL. We further contribute two baselines. HiGA is a trained hierarchical goal assigner on top of a frozen open-vocabulary navigation policy, and LaViRA-M3 is a training-free team of VLM agents with shared mapping and progress analysis. Adapted multi-robot and zero-shot methods reach 16--27% SR, while our baselines reach 38--41% with complementary strengths and distinct failure modes. Furthermore, we deploy LaViRA-M3 on a heterogeneous three-robot team. Project page: https://robo-lavira.github.io/hm3d-m3/

## TL;DR

Rapid progress in AI agents and robotics makes it a matter of the near future that humans are served by a team of robots. Such a team will receive several goals at once, each specified in whatever form is convenient for the human, such as a category name, a photo, or a spoken description.

## Related
<!-- [[other-paper-citekey]] -->
