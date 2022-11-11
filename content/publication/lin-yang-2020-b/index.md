---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Fast and efficient nested simulation for large variable annuity portfolios:
  A surrogate modeling approach'
subtitle: ''
summary: ''
authors:
- X. Sheldon Lin
- Shuai Yang
tags:
- Variable annuity portfolio
- Nested-simulation
- Surrogate modeling
- Spline regression
- Population sampling
categories: []
date: '2020-01-01'
lastmod: 2022-05-27T21:59:42-04:00
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
publishDate: '2022-11-11T20:58:51.513821Z'
publication_types:
- '2'
abstract: The nested-simulation is commonly used for calculating the predictive distribution
  of the total variable annuity (VA) liabilities of large VA portfolios. Due to the
  large numbers of policies, inner-loops and outer-loops, running the nested-simulation
  for a large VA portfolio is extremely time consuming and often prohibitive. In this
  paper, the use of surrogate models is incorporated into the nested-simulation algorithm
  so that the relationship between the inputs and the outputs of a simulation model
  is approximated by various statistical models. As a result, the nested-simulation
  algorithm can be run with much smaller numbers of different inputs. Specifically,
  a spline regression model is used to reduce the number of outer-loops and a model-assisted
  finite population estimation framework is adapted to reduce the number of policies
  in use for the nested-simulation. From simulation studies, our proposed algorithm
  is able to accurately approximate the predictive distribution of the total VA liability
  at a significantly reduced running time.
publication: '*Insurance: Mathematics and Economics*'
doi: https://doi.org/10.1016/j.insmatheco.2020.01.002
---
