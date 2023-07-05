---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Robust Risk-Aware Reinforcement Learning
subtitle: ''
summary: ''
authors:
- Sebastian Jaimungal
- Silvana M. Pesenti
- Ye Sheng Wang
- Hariom Tatsat
tags: []
categories: []
date: '2022-01-01'
lastmod: 2022-07-04T20:52:34-04:00
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
publishDate: '2023-07-05T18:04:28.945060Z'
publication_types:
- '2'
abstract: 'We present a reinforcement learning (RL) approach for robust optimization
  of risk-aware performance criteria. To allow agents to express a wide variety of
  risk-reward profiles, we assess the value of a policy using rank dependent expected
  utility (RDEU). RDEU allows agents to seek gains, while simultaneously protecting
  themselves against downside risk. To robustify optimal policies against model uncertainty,
  we assess a policy not by its distribution but rather by the worst possible distribution
  that lies within a Wasserstein ball around it. Thus, our problem formulation may
  be viewed as an actor/agent choosing a policy (the outer problem) and the adversary
  then acting to worsen the performance of that strategy (the inner problem). We develop
  explicit policy gradient formulae for the inner and outer problems and show their
  efficacy on three prototypical financial problems: robust portfolio allocation,
  benchmark optimization, and statistical arbitrage. '
publication: '*SIAM Journal on Financial Mathematics*'
doi: 10.1137/21M144640X
---
