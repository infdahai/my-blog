---
citekey: "idreesTrackCompleteLearningHumanoidSkillsSingleFailedHuman2026"
title: "Track-and-Complete: Learning Humanoid Skills from a Single Failed Human Video"
authors: ["Sarmad Idrees", "Jongeun Choi"]
year: 2026
venue: "arXiv"
url: "https://arxiv.org/abs/2609.36924"
doi: "10.48550/arXiv.2609.36924"
tags: [paper, embodied-ai, "cs.CV", "cs.RO"]
status: unread
rating:
created: 2026-09-30
---

# Track-and-Complete: Learning Humanoid Skills from a Single Failed Human Video

> Sarmad Idrees, Jongeun Choi · 2026
> [arXiv](https://arxiv.org/abs/2609.36924) · [PDF](https://arxiv.org/pdf/2609.36924)

## Abstract

Learning humanoid skills from videos typically requires a successful human demonstration, which often demands custom data collection. Although failures have traditionally been treated only as negative examples in robot learning, they can still reveal a usable trajectory prefix before the task fails, as well as the intended outcome. To leverage this information from a failed-attempt video, we propose TRACC, a pipeline that imitates the useful portion of the motion trajectory and then completes the task based on the inferred task outcome. The usable motion prefix serves as prior knowledge until the failure occurs, after which the task-completion reward guides the policy to learn the intended task goal without requiring a successful task trajectory. We evaluate our method on six in-the-wild failed human tasks from the Oops! dataset. Our experimental results demonstrate the effectiveness of the proposed approach for learning from failed attempts when no successful demonstration is available. Thus, these findings establish failed human videos as a viable source of supervision for humanoid skill learning.

## TL;DR

Learning humanoid skills from videos typically requires a successful human demonstration, which often demands custom data collection. Although failures have traditionally been treated only as negative examples in robot learning, they can still reveal a usable trajectory prefix before the task fails, as well as the intended outcome.

## Related
<!-- [[other-paper-citekey]] -->
