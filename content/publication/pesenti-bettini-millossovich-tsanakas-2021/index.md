---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Scenario Weights for Importance Measurement (SWIM) – an R package for sensitivity
  analysis
subtitle: ''
summary: ''
authors:
- Silvana M. Pesenti
- Alberto Bettini
- Pietro Millossovich
- Andreas Tsanakas
tags: []
categories: []
date: '2021-01-01'
lastmod: 2022-07-04T20:52:33-04:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-11-12T15:02:20.024334Z'
publication_types:
- '2'
abstract: The Scenario Weights for Importance Measurement (SWIM) package implements
  a flexible sensitivity analysis framework, based primarily on results and tools
  developed by Pesenti et al. (2019). SWIM provides a stressed version of a stochastic
  model, subject to model components (random variables) fulfilling given probabilistic
  constraints (stresses). Possible stresses can be applied on moments, probabilities
  of given events, and risk measures such as Value-At-Risk and Expected Shortfall.
  SWIM operates upon a single set of simulated scenarios from a stochastic model,
  returning scenario weights, which encode the required stress and allow monitoring
  the impact of the stress on all model components. The scenario weights are calculated
  to minimise the relative entropy with respect to the baseline model, subject to
  the stress applied. As well as calculating scenario weights, the package provides
  tools for the analysis of stressed models, including plotting facilities and evaluation
  of sensitivity measures. SWIM does not require additional evaluations of the simulation
  model or explicit knowledge of its underlying statistical and functional relations;
  hence, it is suitable for the analysis of black box models. The capabilities of
  SWIM are demonstrated through a case study of a credit portfolio model.
publication: '*Annals of Actuarial Science*'
doi: 10.1017/S1748499521000130
---
