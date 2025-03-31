---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Stressing dynamic loss models
subtitle: ''
summary: ''
authors:
- Emma Kroell
- Silvana M. Pesenti
- Sebastian Jaimungal
tags: []
categories: []
date: '2024-01-01'
lastmod: 2024-06-16T19:54:50-04:00
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
publishDate: '2025-03-31T18:49:01.596159Z'
publication_types:
- '2'
abstract: 'Stress testing, and in particular, reverse stress testing, is a prominent
  exercise in risk management practice. Reverse stress testing, in contrast to (forward)
  stress testing, aims to find an alternative but plausible model such that under
  that alternative model, specific adverse stresses (i.e. constraints) are satisfied.
  Here, we propose a reverse stress testing framework for dynamic models. Specifically,
  we consider a compound Poisson process over a finite time horizon and stresses composed
  of expected values of functions applied to the process at the terminal time. We
  then define the stressed model as the probability measure under which the process
  satisfies the constraints and which minimizes the Kullback-Leibler divergence to
  the reference compound Poisson model. We solve this optimization problem, prove
  existence and uniqueness of the stressed probability measure, and provide a characterization
  of the Radon-Nikodym derivative from the reference model to the stressed model.
  We find that under the stressed measure, the intensity and the severity distribution
  of the process depend on time and state, and hence the stressed model is not a compound
  Poisson process. We illustrate the dynamic stress testing by considering stresses
  on VaR and both VaR and CVaR jointly and provide illustrations of how the stochastic
  process is altered under these stresses. We generalize the framework to multivariate
  compound Poisson processes and stresses at times other than the terminal time. We
  illustrate the applicability of our framework by considering “what if” scenarios,
  where we answer the question: What is the severity of a stress on a portfolio component
  at an earlier time such that the aggregate portfolio exceeds a risk threshold at
  the terminal time? Furthermore, for general constraints, we propose an algorithm
  to simulate sample paths under the stressed measure, thus allowing to compare the
  effects of stresses on the dynamics of the process.'
publication: '*Insurance: Mathematics and Economics*'
doi: https://doi.org/10.1016/j.insmatheco.2023.11.002
links:
- name: URL
  url: https://www.sciencedirect.com/science/article/pii/S0167668723000975
---
