---
citekey: "campsScaffoldM3CMultimodalSequentialMonteCarloFrameworkGenerativeStable2026"
title: "ScaffoldM3C: A Multimodal Sequential Monte Carlo Framework for Generative Stable Construction Planning"
authors: ["Gadiel Sznaier Camps", "Chengyang He", "Guillaume Sartoretti", "Eduardo Montijano", "Mac Schwager"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.00487"
doi: "10.48550/arXiv.2610.00487"
tags: [paper, embodied-ai, "cs.LG", "cs.RO"]
status: unread
rating:
created: 2026-10-03
---

# ScaffoldM3C: A Multimodal Sequential Monte Carlo Framework for Generative Stable Construction Planning

> Gadiel Sznaier Camps, Chengyang He, Guillaume Sartoretti, Eduardo Montijano, Mac Schwager · 2026
> [arXiv](https://arxiv.org/abs/2610.00487) · [PDF](https://arxiv.org/pdf/2610.00487)

## Abstract

Autonomously constructing physically realizable 3D structures remains a significant challenge due to combinatorial action spaces, interchangeable components, equifinal assembly sequences, and strict stability requirements during construction. State-of-the-art methods fine-tune large language models for text-based generative construction. However, these approaches do not allow for Multimodal (text, image, sketch) conditioning, overlook the practical role of scaffolding for stabilizing intermediate structures, and suffer from slow inference speeds. Therefore, we formulate construction as a probabilistic next-block generation task with multiple potential assembly actions and multiple potential task conditioning modalities. Concurrently, we explicitly consider the utility of scaffolding by introducing an auxiliary scaffold block token. We present Scaffold Multimodal Monte Carlo (ScaffoldM3C), a multimodal, lightweight, auto-regressive model for stable block-based construction, that proposes a set of next-step candidate blocks. Leveraging these candidates, we utilize Sequential Monte Carlo (SMC) to maintain a population of possible assembly sequences, allowing us to consider multiple, potentially different, assembly directions simultaneously. We train our multimodal architecture by extending the StableText2Brick dataset to contain image conditioning prompts and scaffold-stabilized build sequences. ScaffoldM3C is 4x smaller than competing baselines, yielding a 5x to 20x speedup during inference, while achieving comparable construction quality to state-of-the-art methods and higher overall stability. We demonstrate the effectiveness of our approach through simulations and real-world robot assembly demonstrations.

## TL;DR

Autonomously constructing physically realizable 3D structures remains a significant challenge due to combinatorial action spaces, interchangeable components, equifinal assembly sequences, and strict stability requirements during construction. State-of-the-art methods fine-tune large language models for text-based generative construction.

## Related
<!-- [[other-paper-citekey]] -->
