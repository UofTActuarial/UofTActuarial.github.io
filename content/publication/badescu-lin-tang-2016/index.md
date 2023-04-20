---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'A marked Cox model for the number of IBNR claims: Theory'
subtitle: ''
summary: ''
authors:
- Andrei L. Badescu
- X. Sheldon Lin
- Dameng Tang
tags:
- IBNR claims
- Loss reserving
- Cox model
- Hidden Markov chain
- Temporal dependence
- Pascal mixture
categories: []
date: '2016-01-01'
lastmod: 2022-05-30T21:16:34-04:00
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
publishDate: '2023-04-20T19:36:51.263471Z'
publication_types:
- '2'
abstract: Incurred but not reported (IBNR) loss reserving is an important issue for
  Property & Casualty (P&C) insurers. To calculate IBNR reserve, one needs to model
  claim arrivals and then predict IBNR claims. However, factors such as temporal dependence
  among claim arrivals and environmental variation are often not incorporated in many
  of the current loss reserving models, which may greatly affect the accuracy of IBNR
  predictions. In this paper, we propose to model the claim arrival process together
  with its reporting delays as a marked Cox process. Our model is versatile in modeling
  temporal dependence, allowing also for natural interpretations. This paper focuses
  mainly on the theoretical aspects of the proposed model. We show that the associated
  reported claim process and IBNR claim process are both marked Cox processes with
  easily convertible intensity functions and marking distributions. The proposed model
  can also account for fluctuations in the exposure. By an order statistics property,
  we show that the corresponding discretely observed process preserves all the information
  about the claim arrivals. Finally, we derive closed-form expressions for both the
  autocorrelation function (ACF) and the distributions of the numbers of reported
  claims and IBNR claims. Model estimation and its applications are considered in
  a subsequent paper, Badescu et al. (2015b).
publication: '*Insurance: Mathematics and Economics*'
doi: https://doi.org/10.1016/j.insmatheco.2016.03.016
---
