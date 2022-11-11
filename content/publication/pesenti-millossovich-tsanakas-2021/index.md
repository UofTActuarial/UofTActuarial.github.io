---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Cascade Sensitivity Measures
subtitle: ''
summary: ''
authors:
- Silvana M. Pesenti
- Pietro Millossovich
- Andreas Tsanakas
tags:
- dependence
- importance measures
- model uncertainty
- risk measures
- Rosenblatt transform
- Sensitivity analysis
categories: []
date: '2021-01-01'
lastmod: 2022-07-04T20:52:34-04:00
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
publishDate: '2022-11-11T21:07:46.752189Z'
publication_types:
- '2'
abstract: In risk analysis, sensitivity measures quantify the extent to which the
  probability distribution of a model output is affected by changes (stresses) in
  individual random input factors. For input factors that are statistically dependent,
  we argue that a stress on one input should also precipitate stresses in other input
  factors. We introduce a novel sensitivity measure, termed cascade sensitivity, defined
  as a derivative of a risk measure applied on the output, in the direction of an
  input factor. The derivative is taken after suitably transforming the random vector
  of inputs, thus explicitly capturing the direct impact of the stressed input factor,
  as well as indirect effects via other inputs. Furthermore, alternative representations
  of the cascade sensitivity measure are derived, allowing us to address practical
  issues, such as incomplete specification of the model and high computational costs.
  The applicability of the methodology is illustrated through the analysis of a commercially
  used insurance risk model.
publication: '*Risk Analysis*'
doi: https://doi.org/10.1111/risa.13758
---
