---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Delta Boosting Machine with Application to General Insurance
subtitle: ''
summary: ''
authors:
- Simon C. K. Lee
- Sheldon Lin
tags: []
categories: []
date: '2018-01-01'
lastmod: 2022-05-30T21:08:40-04:00
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
publishDate: '2022-07-13T02:05:35.811082Z'
publication_types:
- '2'
abstract: 'In this article, we introduce Delta Boosting (DB) as a new member of the
  boosting family. Similar to the popular Gradient Boosting (GB), this new member
  is presented as a forward stagewise additive model that attempts to reduce the loss
  at each iteration by sequentially fitting a simple base learner to complement the
  running predictions. Instead of relying on the negative gradient, as is the case
  for GB, DB adopts a new measure called delta as the basis. Delta is defined as the
  loss minimizer at an observation level. We also show that DB is the optimal boosting
  member for a wide range of loss functions. The optimality is a consequence of DB
  solving for the split and adjustment simultaneously to maximize loss reduction at
  each iteration. In addition, we introduce an asymptotic version of DB that works
  well for all twice-differentiable strictly convex loss functions. This asymptotic
  behavior does not depend on the number of observations, but rather on a high number
  of iterations that can be augmented through common regularization techniques. We
  show that the basis in the asymptotic extension differs from the basis in GB only
  by a multiple of the second derivative of the log-likelihood. The multiple is considered
  to be a correction factor, one that corrects the bias toward the observations with
  high second derivatives in GB. When negative log-likelihood is used as the loss
  function, this correction can be interpreted as a credibility adjustment for the
  process variance. Simulation studies and real data application we conducted suggest
  that DB is a significant improvement over GB. The performance of the asymptotic
  version is less dramatic, but the improvement is still compelling. Like GB, DB provides
  a high transparency to users, and we can review the marginal influence of variables
  through relative importance charts and the partial dependence plots. We can also
  assess the overall model performance through evaluating the losses, lifts, and double
  lifts on the holdout sample. '
publication: '*North American Actuarial Journal*'
doi: 10.1080/10920277.2018.1431131
---
