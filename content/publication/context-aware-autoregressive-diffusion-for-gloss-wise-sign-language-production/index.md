---
title: Context-Aware Autoregressive Diffusion for Gloss-Wise Sign Language Production
publication_types:
  - paper
authors:
  - Junghoon Sung
  - Boeun Kim
  - Xin Chu
  - Hyungjin Chang
  - Changho Kim
  - Sang-il Kim
  - Younggeun Choi
abstract: "To generate natural and accurate sentence-level sign language,
  synthesizing the ‘gloss’—the fundamental semantic unit is essential. However,
  most current sign language production (SLP) methods generate entire sequences
  at once. While this end-to-end approach is often efficient, it is prone to
  temporal drift and hand motion blur as sentences get longer, and fails to
  accurately control individual glosses. In this paper, we propose the
  Context-Aware Gloss-wise AutoRegressive Diffusion model (GARD), a gloss-wise
  diffusion framework that models coarticulation by conditioning on both
  semantic (linguistic) and kinematic (motion) contexts. To ensure natural
  continuity between gloss motions, GARD introduces two additional strategies:
  i) Inter-Gloss Transition Guidance, which applies gradient-based guidance to
  kinematically align inter-gloss boundaries and ensure seamless pose
  consistency. ii) Global Motion Harmonizer, refining the entire gloss motion
  sequence based on the boundary poses adjusted by Inter-Gloss Transition
  Guidance. Extensive experiments on Phoenix-14T and CSL-Daily datasets
  demonstrate that GARD achieves superior performance over existing SLP methods
  in terms of both linguistic accuracy and motion similarity."
draft: false
featured: false
image:
  filename: aaai.png
  focal_point: Smart
  preview_only: false
date: 2026-08-01T12:45:00.000+09:00
---
