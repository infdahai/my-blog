---
citekey: "oumiSoundBasedMultiPerson3DPoseEstimation2026"
title: "Sound-based Multi-Person 3D Pose Estimation"
authors: ["Yusuke Oumi", "Yuto Shibata", "Go Irie", "Akisato Kimura", "Yoshimitsu Aoki", "Mariko Isogawa"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.04902"
doi: "10.48550/arXiv.2609.04902"
tags: [paper, embodied-ai, "cs.AI", "cs.CV", "cs.LG", "cs.RO", "cs.SD"]
status: unread
rating:
created: 2026-09-08
---

# Sound-based Multi-Person 3D Pose Estimation

> Yusuke Oumi, Yuto Shibata, Go Irie, Akisato Kimura, Yoshimitsu Aoki, Mariko Isogawa · 2026
> [arXiv](https://arxiv.org/abs/2609.04902) · [PDF](https://arxiv.org/pdf/2609.04902)

## Abstract

Can we recover the 3D poses of multiple people using only sound? This paper presents the first attempt to estimate multi-person 3D poses solely from acoustic signals. Estimating the poses of multiple individuals using acoustic signals is inherently challenging due to the superposition of motion-dependent signal variations. Unlike single-person scenarios, the presence of multiple subjects leads to overlapping acoustic signatures, making it difficult to attribute specific signal changes to an individual's pose. Furthermore, the complexity is compounded by inter-person reflections, which introduce intricate propagation delays that obscure the temporal motion-acoustic relationship. To address these issues, we propose SoundMHPE (Sound-based Multi-person Human Pose Estimator), a novel encoder-decoder framework consisting of two key components. First, the Acoustic Multi-scale Encoder captures diverse temporal and fine-grained frequency features to isolate subtle acoustic signatures from complex, overlapping signals. Second, the Temporal Pose Decoder employs an attention mechanism to disentangle multi-person information across successive frames. By jointly accounting for temporal dynamics and inter-person dependencies, this component precisely reconstructs frame-wise individual poses. To validate our approach, we constructed the 6-hour Acoustic Multi-person Pose (AMP) dataset consisting of 432K synchronized frames of multi-person pose and acoustic data, and demonstrated that our SoundMHPE outperforms baseline models. Project page: https://oumi03.github.io/sound-mhpe/

## TL;DR

Can we recover the 3D poses of multiple people using only sound? This paper presents the first attempt to estimate multi-person 3D poses solely from acoustic signals.

## Related
<!-- [[other-paper-citekey]] -->
