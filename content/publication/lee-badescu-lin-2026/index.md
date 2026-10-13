---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "A portfolio-anchored frequency–severity behavioral risk index for trip and driver assessment using telematics signals"
subtitle: ''
summary: ''
authors:
- "Jongtaek Lee"
- "Andrei Badescu"
- "Sheldon Lin"
tags: []
categories: []
date: "2026-09-01"
lastmod: '2026-10-13'
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
publishDate: '2026-07-30T20:03:29.779245Z'
publication_types:
- "2"
abstract: 'In this paper, we propose a frequency–severity joint trip-level behavioral risk index that combines the frequency of driving patterns with a signal severity component reflecting how extreme such patterns are relative to a portfolio-level baseline. The severity is quantified through an inverse-probability penalty that increases with the extremeness/rarity of tail observations, not claim size. For high-frequency telematics data, we construct a multi-scale representation using the Maximal Overlap Discrete Wavelet Transform (MODWT), which preserves driving patterns across multiple time scales. To capture severity as tail extremeness/rarity, we model the portfolio distribution using a Gaussian–Uniform mixture with a layered tail structure, where Gaussian components describe typical driving patterns, and the tail is partitioned into ordered severity layers that reflect increasing extremeness. We develop a likelihood-based estimation procedure that makes inference feasible for this mixture model. The estimated severity layers are used to construct multi-layer tail counts (MLTCs) at the trip level, which are modeled within a Poisson–Gamma framework to yield a closed-form posterior risk index that jointly reflects frequency and severity. This conjugate structure supports sequential updating, enabling the construction of evolving driver-level risk profiles. Using the UAH-DriveSet controlled dataset, we demonstrate that the proposed index separates instructed behavioral states, such as <code>normal</code>, <code>aggressive</code>, and <code>drowsy</code>, and identifies high-risk trips. The proposed model improves binary classification of <code>normal</code> versus <code>risky</code> trips, with sensitivity analyses showing that its performance is stable with respect to the choices of hyperparameters, including the severity weighting function, frequency distribution, and the data thinning phase.'
publication: "*ASTIN Bulletin*"
doi: "10.1017/asb.2026.10112"
links:
- name: URL
  url: https://www.cambridge.org/core/journals/astin-bulletin-journal-of-the-iaa/article/portfolioanchored-frequencyseverity-behavioral-risk-index-for-trip-and-driver-assessment-using-telematics-signals/B126D1D692B1F4162C7F8D18FDAB9A63
---
