---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Improving risk classification and ratemaking using mixture-of-experts models
  with random effects
subtitle: ''
summary: ''
authors:
- Spark C. Tseung
- Ian Weng Chan
- Tsz Chai Fung
- Andrei L. Badescu
- X. Sheldon Lin
tags:
- mixture-of-experts
- random effects
- ratemaking
- risk classification
- variational inference
categories: []
date: -01-01
lastmod: 2023-07-05T14:03:31-04:00
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
publishDate: '2024-06-16T23:06:30.445104Z'
publication_types:
- '2'
abstract: In the underwriting and pricing of nonlife insurance products, it is essential
  for the insurer to utilize both policyholder information and claim history to ensure
  profitability and proper risk management. In this paper, we apply a flexible regression
  model with random effects, called the Mixed Logit-weighted Reduced Mixture-of-Experts,
  which leverages both policyholder information and their claim history, to categorize
  policyholders into groups with similar risk profiles, and to determine a premium
  that accurately captures the unobserved risks. Estimates of model parameters and
  the posterior distribution of random effects can be obtained by a stochastic variational
  algorithm, which is numerically efficient and scalable to large insurance portfolios.
  Our proposed framework is shown to outperform the classical benchmark models (Logistic
  and Lognormal GL(M)M) in terms of goodness-of-fit to data, while offering intuitive
  and interpretable characterization of policyholders' risk profiles to adequately
  reflect their claim history.
publication: '*Journal of Risk and Insurance*'
doi: https://doi.org/10.1111/jori.12436
links:
- name: URL
  url: https://onlinelibrary.wiley.com/doi/abs/10.1111/jori.12436
---
