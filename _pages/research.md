---
title: "Research"
permalink: /research/
author_profile: true
---

## OPTION: Optimal Transport-Guided Flow Matching for Incomplete and Unaligned Multi-View Clustering

**Status:** Submitted to ICML 2026  
**Authors:** Siyuan Zhou, Zhibin Gu

OPTION is a unified framework for multi-view clustering under realistic non-ideal settings, where views may be missing and cross-view sample correspondences may be unknown. The method jointly optimizes missing-view imputation, structural alignment, and clustering. It uses conditional flow matching for efficient latent imputation and Gromov-Wasserstein-inspired structural alignment for correspondence-free multi-view fusion.

- Designed a unified generation-alignment-clustering framework.
- Implemented a conditional flow-matching imputation module with deterministic ODE-based generation.
- Developed a batch-wise structural alignment loss for correspondence-free fusion.
- Evaluated robustness under high missingness and severe cross-view misalignment.

**Paper PDF:** coming soon.  
**Code:** coming soon.

## X-Edit: Exact, Explicit, and Explainable Null-Space Editing for Medical Vision Transformers

**Status:** Submitted to MICCAI 2026  
**Authors:** Yuanye Liu*, Siyuan Zhou*, Ke Zhang, Lei Li, Wei Chen, Xiahai Zhuang

X-Edit develops a theoretically grounded model editing framework for correcting failure cases in medical Vision Transformers without catastrophic forgetting. It combines causal tracing for localizing influential components with null-space constrained closed-form updates to preserve previously learned representations.

- Studied model editing, continual learning, and interpretability in deep neural networks.
- Designed a null-space constrained editing formulation.
- Developed causal tracing for locating error-relevant model components.
- Implemented efficient closed-form post-hoc model updates.
- Evaluated reliability and efficiency on medical imaging benchmarks.

**Paper PDF:** coming soon.

## Scalable Structure-Preserving Multi-View Clustering with Optimal Transport and Density Estimation

**Status:** Research project

This project explores scalable multi-view clustering under heterogeneous feature spaces and varying view quality. The framework integrates sparse feature learning, density-aware view weighting, and landmark-based optimal transport to preserve local and global geometric structures with near-linear computational complexity.

- Designed sparse feature selection with randomized SVD and Laplacian regularization.
- Developed density-aware view weighting using k-NN kernel density estimation.
- Proposed landmark-based optimal transport for graph refinement.
- Integrated local k-NN graph structure with global OT-based geometric information.

## Deep Learning-Based Viral Sequence Identification and Classification Pipeline

**Status:** Research project, Zhu Lab, Fudan University

This project studies computational methods for viral sequence identification and classification in metagenomic data. It compares deep learning-based, alignment-based, and graph-based tools, and develops a unified analysis pipeline for robust and standardized viral sequence classification.

- Studied tools including DNABERT-based models, ViraLM, CheckV, 4CAC, Genomad, Minimap2, and PhaCGN.
- Compared methods in terms of accuracy, robustness, and scalability.
- Analyzed challenges such as short contig classification, dataset bias, and inconsistent taxonomy standards.
- Designed a unified pipeline with standardized outputs and potential ensemble strategies.
