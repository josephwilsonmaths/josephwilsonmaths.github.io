---
title: "Uncertainty Quantification with the Empirical Neural Tangent Kernel"
collection: publications
category: manuscripts
permalink: /publication/2025-01-01-empirical-neural-tangent-kernel
authors: '**Joseph Wilson**, C. van der Heide, L. Hodgkinson, and F. Roosta'
date: 2025-12-12
venue: 'Neural Information Processing Systems (NeurIPS)'
abstract: While neural networks have demonstrated impressive performance across various tasks, accurately quantifying uncertainty in their predictions is essential to ensure their trustworthiness and enable widespread adoption in critical systems. Several Bayesian uncertainty quantification (UQ) methods exist that are either cheap or reliable, but not both. We propose a post-hoc, sampling-based UQ method for over-parameterized networks at the end of training. Our approach constructs efficient and meaningful deep ensembles by employing a (stochastic) gradient-descent sampling process on appropriately linearized networks. We demonstrate that our method effectively approximates the posterior of a Gaussian process using the empirical Neural Tangent Kernel. Through a series of numerical experiments, we show that our method not only outperforms competing approaches in computational efficiency-often reducing costs by multiple factors-but also maintains state-of-the-art performance across a variety of UQ metrics for both regression and classification tasks.
link: https://arxiv.org/abs/2502.02870
---