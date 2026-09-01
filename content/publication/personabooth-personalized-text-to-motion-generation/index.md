---
title: "PersonaBooth: Personalized Text-to-Motion Generation"
publication_types:
  - paper-conference
authors:
  - Boeun Kim
  - Hea In Jeong
  - Junghoon Sung
  - Yihua Cheng
  - Jeongmin Lee
  - Ju Yong Chang
  - Sang-Il Choi
  - Younggeun Choi
  - Saim Shin
  - Jungho Kim
  - Hyung Jin Chang
doi: ""
publication: CVPR2025
publication_short: CVPR2025
abstract: "This paper introduces Motion Personalization, a new task that
  generates personalized motions aligned with text descriptions using several
  basic motions containing Persona. To support this novel task, we introduce a
  new large-scale motion dataset called PerMo (PersonaMotion), which captures
  the unique personas of multiple actors. We also propose a multi-modal
  finetuning method of a pretrained motion diffusion model called PersonaBooth.
  PersonaBooth addresses two main challenges: i) A significant distribution gap
  between the persona-focused PerMo dataset and the pretraining datasets, which
  lack persona-specific data, and ii) the difficulty of capturing a consistent
  persona from the motions vary in content (action type). To tackle the dataset
  distribution gap, we introduce a persona token to accept new persona features
  and perform multi-modal adaptation for both text and visuals during
  finetuning. To capture a consistent persona, we incorporate a contrastive
  learning technique to enhance intra-cohesion among samples with the same
  persona. Furthermore, we introduce a context-aware fusion mechanism to
  maximize the integration of persona cues from multiple input motions.
  PersonaBooth outperforms state-of-the-art motion style transfer methods,
  establishing a new benchmark for motion personalization."
draft: false
featured: false
projects:
  - https://arxiv.org/abs/2503.07390
image:
  filename: cvpr.png
  focal_point: ""
  preview_only: false
date: 2025-05-03T18:20:00.000+09:00
---
