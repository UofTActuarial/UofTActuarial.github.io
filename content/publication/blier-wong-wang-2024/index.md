---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Improved thresholds for e-values
subtitle: ''
summary: ''
authors:
- Christopher Blier-Wong
- Ruodu Wang
tags: []
categories: []
date: '2024-01-01'
lastmod: 2022-07-04T21:06:29-04:00
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
publishDate: '2024-12-09T14:28:02.792513Z'
publication_types:
- '2'
abstract: The rejection threshold used for e-values and e-processes is by default set to 1/α for
 a guaranteed type-I error control at α, based on Markov's and Ville's inequalities. This threshold 
 can be wasteful in practical applications. We discuss how this threshold can be improved under 
 additional distributional assumptions on the e-values; some of these assumptions are naturally 
 plausible and empirically observable, without knowing explicitly the form or model of the e-values. 
 For small values of α, the threshold can roughly be improved (divided) by a factor of 2 for 
 decreasing or unimodal densities, and by a factor of e for decreasing or unimodal-symmetric 
 densities of the log-transformed e-value. Moreover, we propose to use the supremum of comonotonic 
 e-values, which is shown to preserve the type-I error guarantee. We also propose some preliminary 
 methods to boost e-values in the e-BH procedure under some distributional assumptions while 
 controlling the false discovery rate. Through a series of simulation studies, we demonstrate the 
 effectiveness of our proposed methods in various testing scenarios, showing enhanced power.
publication: '*arXiv:2408.11307 (math)*'
links:
- name: URL
  url: https://arxiv.org/abs/2408.11307
doi: https://doi.org/10.48550/arXiv.2408.11307
---
