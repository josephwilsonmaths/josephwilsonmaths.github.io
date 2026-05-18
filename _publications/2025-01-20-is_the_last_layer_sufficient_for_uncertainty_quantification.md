---
title: "Is the Last Layer Sufficient for Uncertainty Quantification?"
collection: publications
category: manuscripts
permalink: /publication/2025-01-20-is_the_last_layer_sufficient_for_uncertainty_quantification
authors: '**Joseph Wilson**, C. van der Heide, L. Hodgkinson, and F. Roosta'
date: 2026-05-01
venue: 'International Conference on Machine Learning (**ICML**, accepted)'
abstract: 'Epistemic uncertainty quantification (UQ) for deep neural networks (DNNs) is a requirement for safe adoption of AI in mission-critical settings. Several leading methods for UQ linearize DNNs to form Bayesian Generalized Linear Models (GLMs), where epistemic uncertainty is modeled via the predictive posterior distribution. Linearizing around the parameters of the final connected layer of a DNN is a commonly used approximation for reducing the computational burden of such GLMs, though it is often believed to come at the cost of degraded performance. In this work, we compare GLMs arising from full-network and last-layer linearization using both theoretical and empirical approaches. We first employ tools from random matrix theory to conduct a theoretical comparison; this analysis reveals no meaningful improvement in the UQ capabilities of full linearization. Coupled with a large-scale empirical evaluation across a range of modern machine learning tasks, we arrive at the following conclusion: a last-layer approximation yields comparable UQ performance while offering substantially improved computational efficiency.'
link: 'https://openreview.net/forum?id=MocMOzHHcV&referrer=%5BAuthor%20Console%5D(%2Fgroup%3Fid%3DICML.cc%2F2026%2FConference%2FAuthors%23your-submissions)'
---