---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "LRMoE Package"
summary: "Logit-weighted Reduced Mixture of Experts model, packages available in Julia and R."
authors: []
tags: []
categories: []
date:
show_date: false

# Optional external URL for project (replaces project detail page).
# external_link: "https://sbolstandard.org/"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
# image:
#   caption: ""
#   focal_point: ""
#   preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# url_code: ""
# url_pdf: ""
# url_slides: ""
# url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: ""
---

LRMoE packages are available in Julia and R.
- In Julia: [documentation](https://uoftactuarial.github.io/LRMoE.jl/)
- In R: [documentation](https://uoftactuarial.github.io/LRMoE/)

---

LRMoE is a package tailor-made for actuarial applications which allows actuarial researchers and practitioners to model and analyze insurance loss frequencies and severities using the Logit-weighted Reduced Mixture-of-Experts (LRMoE) model. The flexibility of LRMoE models is theoretically justified in [Fung et al. (2019)](/publication/fung-badescu-lin-2019-b/), and an application of LRMoE for modelling correlated insurance claim frequencies is in [Fung et al. (2019)](/publication/fung-badescu-lin-2019/).

The package LRMoE offers several new distinctive features which are motivated by various actuarial applications and mostly cannot be achieved using existing packages for mixture models. Key features include:
- A wider coverage on frequency and severity distributions and their zero inflation;
- The flexibility to vary classes of distributions across components;
- Parameter estimation under data censoring and truncation;
- A collection of insurance rate making and reserving functions; and
- Model selection and visualization tools.

While LRMoE was initially developed for actuarial application, this package also allows for customized expert functions for various modelling problems outside of the insurance context.