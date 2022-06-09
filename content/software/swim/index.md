---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "SWIM Package"
summary: "Scenario Weights for Importance Measurement, package available in R and Shiny app."
date: "2022-01-09T00:00:00Z" 
# date as to be earlier than today's date for the page to show; default is to set to package's last update date

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

SWIM package is available in R and Shiny app.
- In R: available via [CRAN](https://cran.r-project.org/web/packages/SWIM/index.html/) and [Github](https://github.com/spesenti/SWIM/)
- In Shiny app: [application](https://icmr.shinyapps.io/ShinySWIM/)

---

The SWIM package provides weights on simulated scenarios from a stochastic model, such that stressed model components (random variables) fulfil given probabilistic constraints (e.g. specified values for risk measures), under the new scenario weights. Scenario weights are selected by constrained minimisation of the relative entropy to the baseline model. The SWIM package is based on the papers [Pesenti et al. (2019)](/publication/pesenti-millossovich-tsanakas-2019) and [Pesenti (2021)](/publication/pesenti-2021).