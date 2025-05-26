---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Assessing driving risk through unsupervised detection of anomalies in telematics
  time series data
subtitle: ''
summary: ''
authors:
- Ian Weng Chan
- Andrei L. Badescu
- X. Sheldon Lin
tags: []
categories: []
date: '2025-01-01'
lastmod: 2025-04-01T22:34:08-04:00
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
publishDate: '2025-05-26T20:04:05.805531Z'
publication_types:
- '2'
abstract: Vehicle telematics provides granular data for dynamic driving risk assessment,
  but current methods often rely on aggregated metrics (e.g., harsh braking counts)
  and do not fully exploit the rich time-series structure of telematics data. In this
  paper, we introduce a flexible framework using continuous-time hidden Markov model
  (CTHMM) to model and analyse trip-level telematics data. Unlike existing methods,
  the CTHMM models raw time-series data without predefined thresholds on harsh driving
  events or assumptions about accident probabilities. Moreover, our analysis is based
  solely on telematics data, requiring no traditional covariates such as driver or
  vehicle characteristics. Through unsupervised anomaly detection based on pseudo-residuals,
  we identify deviations from normal driving patterns—defined as the prevalent behaviour
  observed in a driver’s history or across the population—which are linked to accident
  risk. Validated on both controlled and real-world datasets, the CTHMM effectively
  detects abnormal driving behaviour and trips with increased accident likelihood.
  In real data analysis, higher anomaly levels in longitudinal and lateral accelerations
  consistently correlate with greater accident risk, with classification models using
  this information achieving ROC-AUC values as high as 0.86 for trip-level analysis
  and 0.78 for distinguishing drivers with claims. Furthermore, the methodology reveals
  significant behavioural differences between drivers with and without claims, offering
  valuable insights for insurance applications, accident analysis, and prevention.
publication: '*ASTIN Bulletin*'
doi: 10.1017/asb.2025.14
---
