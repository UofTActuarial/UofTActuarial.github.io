---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Robustness regions for measures of risk aggregation
subtitle: ''
summary: ''
authors:
- Silvana M. Pesenti
- Pietro Millossovich
- Andreas Tsanakas
tags: []
categories: []
date: '2016-01-01'
lastmod: 2022-07-04T20:37:57-04:00
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
publishDate: '2023-04-24T01:01:11.665018Z'
publication_types:
- '2'
abstract: One of risk measures’ key purposes is to consistently rank and distinguish
  between different risk profiles. From a practical perspective, a risk measure should
  also be robust, that is, insensitive to small perturbations in input assumptions.
  It is known in the literature [14, 39], that strong assumptions on the risk measure’s
  ability to distinguish between risks may lead to a lack of robustness. We address
  the trade-off between robustness and consistent risk ranking by specifying the regions
  in the space of distribution functions, where law-invariant convex risk measures
  are indeed robust. Examples include the set of random variables with bounded second
  moment and those that are less volatile (in convex order) than random variables
  in a given uniformly integrable set. Typically, a risk measure is evaluated on the
  output of an aggregation function defined on a set of random input vectors. Extending
  the definition of robustness to this setting, we find that law-invariant convex
  risk measures are robust for any aggregation function that satisfies a linear growth
  condition in the tail, provided that the set of possible marginals is uniformly
  integrable. Thus, we obtain that all law-invariant convex risk measures possess
  the aggregation-robustness property introduced by [26] and further studied by [40].
  This is in contrast to the widely-used, non-convex, risk measure Value-at-Risk,
  whose robustness in a risk aggregation context requires restricting the possible
  dependence structures of the input vectors.
publication: '*Dependence Modeling*'
doi: doi:10.1515/demo-2016-0020
---
