---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Reverse Sensitivity Analysis for Risk Modelling
subtitle: ''
summary: ''
authors:
- Silvana M. Pesenti
tags: []
categories: []
date: '2022-01-01'
lastmod: 2022-06-08T21:09:14-04:00
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
publishDate: '2025-05-26T20:03:39.747607Z'
publication_types:
- '2'
abstract: We consider the problem where a modeller conducts sensitivity analysis of
  a model consisting of random input factors, a corresponding random output of interest,
  and a baseline probability measure. The modeller seeks to understand how the model
  (the distribution of the input factors as well as the output) changes under a stress
  on the output’s distribution. Specifically, for a stress on the output random variable,
  we derive the unique stressed distribution of the output that is closest in the
  Wasserstein distance to the baseline output’s distribution and satisfies the stress.
  We further derive the stressed model, including the stressed distribution of the
  inputs, which can be calculated in a numerically efficient way from a set of baseline
  Monte Carlo samples and which is implemented in the R package SWIM on CRAN. The
  proposed reverse sensitivity analysis framework is model-free and allows for stresses
  on the output such as (a) the mean and variance, (b) any distortion risk measure
  including the Value-at-Risk and Expected-Shortfall, and (c) expected utility type
  constraints, thus making the reverse sensitivity analysis framework suitable for
  risk models.
publication: '*Risks*'
links:
- name: URL
  url: https://www.mdpi.com/2227-9091/10/7/141
doi: 10.3390/risks10070141
---
