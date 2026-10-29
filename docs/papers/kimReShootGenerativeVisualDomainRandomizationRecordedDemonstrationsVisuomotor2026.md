---
citekey: "kimReShootGenerativeVisualDomainRandomizationRecordedDemonstrationsVisuomotor2026"
title: "ReShoot: Generative Visual Domain Randomization of Recorded Robot Demonstrations for Visuomotor Policy Learning"
authors: ["Chiyoung Kim", "Min Sung Choi", "Jinho Ju", "Chanhoe Gu", "Donghwan Hwang", "Wonseok Choi", "Woongsun Jeon", "Minhyeok Lee"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.19661"
doi: "10.48550/arXiv.2609.19661"
tags: [paper, embodied-ai, "cs.RO"]
status: unread
rating:
created: 2026-09-18
---

# ReShoot: Generative Visual Domain Randomization of Recorded Robot Demonstrations for Visuomotor Policy Learning

> Chiyoung Kim, Min Sung Choi, Jinho Ju, Chanhoe Gu, Donghwan Hwang, Wonseok Choi, Woongsun Jeon, Minhyeok Lee · 2026
> [arXiv](https://arxiv.org/abs/2609.19661) · [PDF](https://arxiv.org/pdf/2609.19661)

## Abstract

Imitation-learned robot policies are frequently overfit to the visual conditions present in their training demonstrations. Consequently, variations in object color or background appearance often induce substantial performance degradation. A common mitigation strategy is to acquire additional demonstrations in each novel visual context; however, this approach is resource-intensive, requiring repeated access to a robot, a controlled environment, and human operation for every appearance condition to be covered. We introduce ReShoot, a framework that synthesizes visual diversity by re-rendering previously recorded demonstrations under altered appearances, thereby shifting the burden from data collection to generation. A vision-language model captions the scene, edits a targeted attribute (e.g., background, object color, or material), and an edge-conditioned video generator re-renders both camera views to match. The instruction is updated accordingly. The action sequence and proprioceptive trajectory are copied verbatim without relabeling, so each generated episode retains the recorded action and proprioceptive labels. On LIBERO, a policy trained on an equal mixture of recorded and re-rendered demonstrations matches the performance of recorded-only training (96.5% vs. 96.9%). Moreover, the mixed training set improves robustness to scene perturbations on LIBERO-Plus (85.5% vs. 82.3%). Across two physical robotic platforms, deploying ReShoot with 43 and 100 pre-collected demonstrations increased the success rate on recolored objects from 0.0% to 42.9% and 47.5%, respectively, while maintaining performance under the original recorded appearance.

## TL;DR

Imitation-learned robot policies are frequently overfit to the visual conditions present in their training demonstrations. Consequently, variations in object color or background appearance often induce substantial performance degradation.

## Related
<!-- [[other-paper-citekey]] -->
