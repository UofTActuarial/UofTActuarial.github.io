---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A Portfolio-Anchored Frequency-Severity Risk Index for Trip and Driver Assessment Using Telematics Signals
subtitle: ''
summary: ''
authors:
- Jongtaek Lee
- Andrei L. Badescu
- X. Sheldon Lin
tags: []
categories: []
date: '2026-03-16'
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
publishDate: '2026-03-16T20:03:29.779245Z'
publication_types:
- '2'
abstract: 'In this paper, we propose a novel frequency-severity joint trip-level risk index that combines the frequency of abnormal driving patterns with a severity component reflecting how extreme such behavior is relative to a portfolio-level baseline. Severity is quantified through an inverse-probability penalty that increases with the rarity of observed tail extremes, rather than being interpreted as a claim size. Based on high-frequency telematics data, we construct a multi-scale representation of longitudinal acceleration using the maximal overlap discrete wavelet transform (MODWT), which preserves localized driving patterns across multiple time scales. To capture severity as tail rarity, we model the portfolio distribution using a Gaussian-Uniform mixture with a layered tail structure, where Gaussian components describe typical driving behavior and the tail is partitioned into ordered severity layers that reflect increasing extremeness. We develop a likelihood-based estimation procedure that makes inference feasible for this mixture model. The resulting severity layers are then used to construct multi-layer tail counts (MLTC) at the trip level, which are modeled within a Poisson-Gamma framework to yield a closed-form posterior risk index that jointly reflects frequency and severity. This conjugate structure naturally supports sequential updating, enabling the construction of dynamically evolving driver-level risk profiles. Using the UAH-DriveSet controlled dataset, we demonstrate that the proposed index enables reliable discrimination across behavioral driving states, identification of high-risk trips, and coherent ranking of drivers, yielding a purely behavior-driven risk measure suitable for actuarial ratemaking and potentially mitigating fairness concerns associated with traditional covariates.'
publication: '*arXiv*'
doi: 10.48550/arXiv.2603.15839
---
