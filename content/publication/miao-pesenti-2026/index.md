---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Discrimination-insensitive pricing
subtitle: ''
summary: ''
authors:
- Kathleen Miao
- Silvana Pesenti
tags: []
categories: []
date: '2026-03-27'
lastmod: 2022-05-27T21:48:51-04:00
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
publishDate: '2026-03-27T20:03:29.779245Z'
publication_types:
- '2'
abstract: 'Rendering fair prices for financial, credit, and insurance products is of ethical and regulatory interest. In many jurisdictions, discriminatory covariates, such as gender and ethnicity, are prohibited from use in pricing such instruments. In this work, we propose a discrimination-insensitive pricing framework, where we require the pricing principle to be insensitive to the (exogenously determined) protected covariates, that is the sensitivity of the pricing principle to the protected covariate is zero. We formulate and solve the optimisation problem that finds the nearest (in Kullback-Leibler (KL) divergence) "pricing" measure to the real world probability, such that under this pricing measure the principle is discrimination-insensitive. We call the solution the discrimination-insensitive measure and provide conditions for its existence and uniqueness. In situations when there are more than one protected covariates, the discrimination-insensitive pricing measure might not exist, and we propose a two-step procedure. First, for each protected covariate separately, we find the measure under which the pricing principle becomes insensitivity to that covariate. Second we reconcile these measures through a constrained barycentre model. We provide a close-form solution to this problem and give conditions for existence and uniqueness of the constrained barycentre pricing measure. As an intermediary result, we prove the representation, existence, and uniqueness of the KL barycentre of general probability measures, which may be of independent interest. Finally, in a numerical illustration, we compare our discrimination-insensitive premia and the constrained barycentre pricing measure with recently proposed fair premia from the actuarial literature.'
publication: '*arXiv*'
doi:  10.48550/arXiv.2603.16720
---
