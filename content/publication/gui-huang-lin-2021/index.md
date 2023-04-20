---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Fitting multivariate Erlang mixtures to data: A roughness penalty approach'
subtitle: ''
summary: ''
authors:
- Wenyong Gui
- Rongtan Huang
- X. Sheldon Lin
tags:
- Multivariate Erlang mixtures
- Truncated and censored data
- GECM algorithm
- Roughness penalty
categories: []
date: '2021-01-01'
lastmod: 2022-05-27T21:48:52-04:00
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
publishDate: '2023-04-20T20:06:39.284454Z'
publication_types:
- '2'
abstract: The class of multivariate Erlang mixtures with common scale parameter has
  many desirable properties and has widely been used in insurance loss modeling. The
  parameters of a multivariate Erlang mixture are normally estimated using an expectation–maximization
  (EM) algorithm as shown in Lee and Lin (2012) and Verbelen et al. (2016). However,
  when fitting the mixture to data of high dimension, the fitted density surface is
  often not smooth (with deep peaks and valleys) and the tail fitting may also be
  rather unsatisfactory. In this paper, we propose a generalized expectation conditional
  maximization (GECM) algorithm that maximizes a penalized likelihood with a proposed
  roughness penalty. The roughness penalty is based on integrated squared second derivative
  of the density function of aggregate data, which is used in functional data analysis.
  We illustrate the performance of the proposed method through some numerical experiments
  and real data applications.
publication: '*Journal of Computational and Applied Mathematics*'
doi: https://doi.org/10.1016/j.cam.2020.113216
---
