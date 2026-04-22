---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'A Unified Bayesian Collective Reserving Framework with Hierarchical Temporal Smoothing'
subtitle: ''
summary: ''
authors:
- Hassan Abdelrahman
- Andrei Badescu
- Sheldon Lin
tags: []
categories: []
date: '2026-03-13'
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
publishDate: '2026-03-13T20:03:56.809829Z'
publication_types:
- '2'
abstract: 'This paper develops a unified Bayesian reserving framework built upon the foundations of the Collective Reserving Model (CRM). Rather than proposing a single fixed specification, we introduce a modular probabilistic architecture that enables the principled integration of structural components commonly encountered in actuarial practice. These include hierarchical partial pooling across claim types, smooth temporal dynamics, spline-based development patterns, calendar effects, seasonal components, reporting--payment delay interactions, and portfolio-level risk covariates.By utilizing Hamiltonian Monte Carlo implemented in \texttt{Stan}, all framework components are estimated jointly within a single coherent likelihood, allowing for a separate estimation of the RBNS and IBNR reserves. This unified formulation ensures full propagation of parameter and process uncertainty across modeling layers and yields robust posterior predictive distributions for reserve risk assessment.Applied to a large European automobile physical damage portfolio, the framework demonstrates a strong ability to extract stable, high-resolution signals from granular monthly data. A rolling-origin backtest shows that the proposed approach substantially outperforms traditional deterministic benchmarks. Ultimately, the results demonstrate that a structured Bayesian approach provides a flexible, interpretable, and practically effective alternative to traditional reserving models.'
publication: '*SSRN Preprint*'
links:
- name: URL
  url: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6410160
---
