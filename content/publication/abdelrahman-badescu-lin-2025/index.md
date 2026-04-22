---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'An Effective Bayesian GLM Approach for IBNR Claim Count Estimation'
subtitle: ''
summary: ''
authors:
- Hassan Abdelrahman
- Andrei Badescu
- Sheldon Lin
tags: []
categories: []
date: '2025-12-01'
lastmod: 2024-11-08T21:16:05-05:00
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
publishDate: '2025-12-01T20:03:56.809829Z'
publication_types:
- '2'
abstract: 'Estimating the count of incurred but not reported (IBNR) claims is a fundamental challenge in loss reserving. The Chain Ladder method, a widely used macro-level approach, relies on aggregated claims data and provides a simple framework for reserve estimation. However, it can be inaccurate in many cases as it does not leverage detailed claims information and may introduce biases under certain conditions. To address these limitations, micro-level models have been developed to incorporate individual claim data, capturing claim occurrence and reporting dynamics more effectively. Recent literature has shown that these models outperform the Chain Ladder method in predictive accuracy. Despite their better performance, micro-level models remain largely unused in practice due to their computational complexity and various modeling challenges, such as fitting right-truncated reporting delay distributions and maximizing likelihood functions with interdependent components. The aim of this article is twofold: first, to provide a comprehensive analysis of existing micro-level models, and second, to propose a highly flexible Bayesian framework that builds on the Chain Ladder method while incorporating key micro-level elements such as temporal dynamics and portfolio-level covariates. Crucially, our framework is designed for practical adoption: Thanks to modern probabilistic programming tools like Stan and the complete, reproducible code provided, practitioners can readily implement and adapt the model without dealing with complex estimation routines. Through a case study, we demonstrate that our framework not only outperforms the classical Chain Ladder method but also surpasses micro-level models adopted in recent literature, offering a scalable, interpretable, and easily implementable solution for IBNR claim count estimation.'
publication: '*North American Actuarial Journal*'
links:
- name: URL
  url: https://www.tandfonline.com/doi/full/10.1080/10920277.2025.2587884
---
