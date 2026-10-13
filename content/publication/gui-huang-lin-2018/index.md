---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Fitting the Erlang mixture model to data via a GEM-CMM algorithm
subtitle: ''
summary: ''
authors:
- "Wenyong Gui"
- "Rongtan Huang"
- "Sheldon Lin"
tags:
- Erlang mixture model
- Insurance loss data
- Generalized EM algorithm
- Clusterized method of moments
- Local search method
categories: []
date: '2018-12-01'
lastmod: '2026-10-13'
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
publishDate: '2025-05-26T20:03:35.847227Z'
publication_types:
- '2'
abstract: The Erlang mixture model with common scale parameter is flexible and analytically
  tractable. As such, it is a useful model to fit insurance loss data and to calculate
  quantities of interest for insurance risk management. In this paper, we propose
  a generalized expectation–maximization (GEM) algorithm along with a clusterized
  method of moments (CMM) to estimate the model parameters. The GEM algorithm not
  only estimates the mixing weights and scale parameter of the model but also estimates
  the shape parameters of the model using a local search method. The CMM method enables
  to produce quality initial estimates for the GEM algorithm. As a result, the proposed
  approach provides an efficient algorithm that can fit the model to the body and
  the tail of truncated and censored loss data well and converges fast. We examine
  the performance of the proposed approach through several simulation studies and
  apply it to fit the Erlang mixture model to two real loss data sets.
publication: '*Journal of Computational and Applied Mathematics*'
doi: '10.1016/j.cam.2018.04.032'
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0377042718302140
---
