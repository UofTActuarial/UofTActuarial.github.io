---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Efficient dynamic hedging for large variable annuity portfolios with multiple
  underlying assets
subtitle: ''
summary: ''
authors:
- X. Sheldon Lin
- Shuai Yang
tags: []
categories: []
date: '2020-01-01'
lastmod: 2022-05-27T21:49:20-04:00
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
publishDate: '2024-11-09T02:15:42.978693Z'
publication_types:
- '2'
abstract: A variable annuity (VA) is an equity-linked annuity that provides investment
  guarantees to its policyholder and its contributions are normally invested in multiple
  underlying assets (e.g., mutual funds), which exposes VA liability to significant
  market risks. Hedging the market risks is therefore crucial in risk managing a VA
  portfolio as the VA guarantees are long-dated liability that may span over decades.
  In order to hedge the VA liability, the issuing insurance company would need to
  construct a hedging portfolio consisting of the underlying assets whose positions
  are often determined by the liability Greeks such as partial dollar Deltas. Usually,
  these quantities are calculated via nested simulation. For insurance companies that
  manage large VA portfolios (e.g.,100K+ policies), calculating those quantities is
  extremely time-consuming or even prohibitive due to the complexity of the guarantee
  payoffs and the stochastic-on-stochastic nature of the nested simulation algorithm.
  In this paper, we extend the surrogate model-assisted nest simulation approach in
  Lin &Yang (2020) to efficiently calculate the total VA liability and the partial
  dollar Deltas for large VA portfolios with multiple underlying assets. In our proposed
  algorithm, the nested simulation is run using small sets of selected representative
  policies and representative outer-loops. As a result, the computing time is substantially
  reduced. The computational advantage of the proposed algorithm and the importance
  of dynamic hedging are further illustrated through a profit and loss (P&L) analysis
  for a large synthetic VA portfolio. Moreover, the robustness of the performance
  of the proposed algorithm is tested with multiple simulation runs. Numerical results
  show that the proposed algorithm is able to accurately approximate different quantities
  of interest and the performance is robust with respect to different sets of parameter
  inputs.
publication: '*ASTIN Bulletin*'
doi: 10.1017/asb.2020.26
---
