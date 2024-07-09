---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Effective Experience Rating for Large Insurance Portfolios via Surrogate Modeling
subtitle: ''
summary: ''
authors:
- Sebastian Calcetero Vanegas
- Andrei Badescu
- X. Sheldon Lin
tags: []
categories: []
date: '2022-01-01'
lastmod: 2022-11-12T09:58:37-05:00
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
publishDate: '2024-07-09T14:28:16.306205Z'
publication_types:
- '2'
abstract: Experience rating in insurance uses a Bayesian credibility model to upgrade
  the current premiums of a contract by taking into account policyholders' attributes
  and their claim history. Most data-driven models used for this task are mathematically
  intractable, and premiums must be obtained through numerical methods such as simulation
  via MCMC. However, these methods can be computationally expensive and even prohibitive
  for large portfolios when applied at the policyholder level. Additionally, these
  computations become \"black-box\" procedures as there is no analytical expression
  showing how the claim history of policyholders is used to upgrade their premiums.
  To address these challenges, this paper proposes a surrogate modeling approach to
  inexpensively derive an analytical expression for computing the Bayesian premiums
  for any given model, approximately. As a part of the methodology, the paper introduces
  a likelihoodbased summary statistic of the policyholder's claim history that serves
  as the main input of the surrogate model and that is sufficient for certain families
  of distribution, including the exponential dispersion family. As a result, the computational
  burden of experience rating for large portfolios is reduced through the direct evaluation
  of such analytical expression, which can provide a transparent and interpretable
  way of computing Bayesian premiums.
publication: '*Available at SSRN 4275353*'
links:
- name: URL
  url: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4275353
---
