---
title: "SMART: MLLM-guided Temporal Alignment for Unifying Sign Language
  Recognition and Spotting"
subtitle: ""
publication_types:
  - paper-conference
authors:
  - Eunji Choi
  - Junghoon Sung
  - Seongwhan Cho
  - Xin Chu
  - Younggeun Choi
publication: British Machine Vision Conference
publication_short: BMVC2026
abstract: Continuous sign language recognition (CSLR) aims to recognize gloss
  sequences from unsegmented sign videos under weak sequence-level supervision.
  However, existing methods rely on sentence-level gloss annotations, providing
  limited temporal and semantic guidance for fine-grained representation
  learning. Conventional video-text alignment also requires large batch sizes,
  making it inefficient for memory-intensive sign language video training. In
  this work, we propose SMART, an MLLM-guided temporal alignment framework for
  joint sign recognition and spotting. SMART uses MLLM-generated motion
  descriptions as auxiliary semantic cues and performs stable video-text
  alignment under small-batch training. To improve temporal representation
  learning, we introduce a Multi-Scale Temporal Adapter that models temporal
  interactions during transformer encoding. For dense temporal localization,
  SMART incorporates CSFormer, a CSLR-guided spotting module that injects
  recognition-derived gloss evidence into a boundary-aware spotting network.
  This unified framework enables CSLR features to benefit spotting, while
  spotting supervision complements weak CTC-based recognition. Experiments on
  four sign language benchmarks, including PHOENIX14-T, CSL-Daily, Large-scale
  KSL, and Disaster and Safety KSL datasets, demonstrate the effectiveness of
  SMART across both recognition and spotting tasks.
draft: false
featured: false
tags:
  - "2026"
image:
  filename: bmvc2026.png
  focal_point: RIGHT
  preview_only: false
date: 2026-07-01T11:16:00.000+09:00
---
