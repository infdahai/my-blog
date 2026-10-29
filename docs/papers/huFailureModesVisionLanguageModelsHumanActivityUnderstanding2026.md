---
citekey: "huFailureModesVisionLanguageModelsHumanActivityUnderstanding2026"
title: "Failure Modes of Vision-Language Models for Human Activity Understanding in Thermal HRI"
authors: ["Han Hu", "He Chen"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2610.29244"
doi: "10.48550/arXiv.2610.29244"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-10-23
---

# Failure Modes of Vision-Language Models for Human Activity Understanding in Thermal HRI

> Han Hu, He Chen · 2026
> [arXiv](https://arxiv.org/abs/2610.29244) · [PDF](https://arxiv.org/pdf/2610.29244)

## Abstract

Thermal cameras enable robots to perceive human activities in darkness while revealing less personally identifiable appearance information and fewer details of the surrounding environment than RGB cameras. As vision-language models (VLMs), originally developed for RGB imagery, are increasingly integrated into embodied systems for scene understanding and high-level planning, thermal sensing offers a promising way to extend activity perception to low-light and privacy-sensitive settings. However, the failure modes of VLMs in thermal human activity understanding for human-robot interaction (HRI) remain underexplored. We fill this gap by evaluating seven locally deployable VLMs, including models developed for physical AI and robotics, on two person-centric thermal datasets. Our diagnostic tasks examine fine-grained action recognition, activity timeline reconstruction, and the ability to withhold unsupported answers. Paired RGB recordings serve as a performance reference, while controlled variations in frame sampling, thermal input presentation, and reasoning are used to assess whether the observed errors can be mitigated. Our results show that models can recognize broad activity categories but struggle with fine-grained actions such as coughing, sneezing, and yawning. They also produce inaccurate event timelines and hallucinate actions involving objects. Simple thermal input preprocessing and additional reasoning offer only limited, model-dependent gains. Abstention behavior also varies across models even under explicit instructions, limiting their reliability for practical robotic use.

## TL;DR

Thermal cameras enable robots to perceive human activities in darkness while revealing less personally identifiable appearance information and fewer details of the surrounding environment than RGB cameras. As vision-language models (VLMs), originally developed for RGB imagery, are increasingly integrated into embodied systems for scene understanding and high-level planning, thermal sensing offers a promising way to extend activity perception to low-light and privacy-sensitive settings.

## Related
<!-- [[other-paper-citekey]] -->
