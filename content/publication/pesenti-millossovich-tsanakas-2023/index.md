---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Differential Sensitivity in Discontinuous Models
subtitle: ''
summary: ''
authors:
- Silvana M Pesenti
- Pietro Millossovich
- Andreas Tsanakas
tags: []
categories: []
date: '2023-01-01'
lastmod: 2024-06-16T19:54:52-04:00
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
publishDate: '2024-11-09T01:29:22.390244Z'
publication_types:
- '2'
abstract: Differential sensitivity measures provide valuable tools for interpreting
  complex computational models used in applications ranging from simulation to algorithmic
  prediction. Taking the derivative of the model output in direction of a model parameter
  can reveal input-output relations and the relative importance of model parameters
  and input variables. Nonetheless, it is unclear how such derivatives should be taken
  when the model function has discontinuities and/or input variables are discrete.
  We present a general framework for addressing such problems, considering derivatives
  of quantile-based output risk measures, with respect to distortions to random input
  variables (risk factors), which impact the model output through step-functions.
  We prove that, subject to weak technical conditions, the derivatives are well-defined
  and derive the corresponding formulas. We apply our results to the sensitivity analysis
  of compound risk models and to a numerical study of reinsurance credit risk in a
  multi-line insurance portfolio.
publication: '*Available at SSRN 4597400*'
links:
- name: URL
  url: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4597400
---
