---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Marked Cox Models for IBNR Claims Count: Continuous and Discretized Approaches
  with Dirichlet-Driven Reporting Delays'
subtitle: ''
summary: ''
authors:
- Hassan Abdelrahman
- Andrei Badescu
- Radu Craiu
- Sheldon Lin
tags: []
categories: []
date: '2024-01-01'
lastmod: 2024-11-08T21:16:05-05:00
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
publishDate: '2025-05-26T20:03:56.809829Z'
publication_types:
- '2'
abstract: 'Accurate loss reserving is crucial in Property and Casualty (P&C) insurance
  for financial stability, regulatory compliance, and effective risk management. We
  propose a novel micro-level Cox model based on hidden Markov models (HMMs). Initially
  formulated as a continuous-time model, it addresses the complexity of incorporating
  temporal dependencies and policyholder risk attributes. However, the continuous-time
  model faces significant challenges in maximizing the likelihood and fitting right-truncated
  reporting delays. To overcome these issues, we introduce two discrete-time versions:
  one incorporating unsystematic randomness in reporting delays through a Dirichlet
  distribution and one without. We provide the EM algorithm for parameter estimation
  for all three models and apply them to an auto-insurance dataset to estimate IBNR
  claim counts. Our results show that while all models perform well, the discrete-time
  versions demonstrate superior performance by jointly modeling delay and frequency,
  with the Dirichlet-based model capturing additional variability in reporting delays.
  This approach enhances the accuracy and reliability of IBNR reserving, offering
  a flexible framework adaptable to different levels of granularity within an insurance
  portfolio.'
publication: '*arXiv*'
links:
- name: URL
  url: https://arxiv.org/abs/2409.12896
---
