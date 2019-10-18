---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Case-Crossover"
authors: [Alex Stringer, Patrick Brown, Jamie Stafford]
date: 2019-10-18T13:57:18-04:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-10-18T13:57:18-04:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Approximate Bayesian Inference for Case Crossover Models"
publication_short: ""

abstract: "A case-crossover analysis is used as a simple but powerful tool for estimating the effect of short-term
environmental factors such as extreme temperatures or poor air quality on mortality. The environment on the day of
each death is compared to the one or more “control days” in previous weeks, and higher levels of exposure on death
days than control days provides evidence of an effect. Current state-of-the-art methodology and software (INLA)
cannot be used to fit the most flexible case-crossover models to large datasets, because these models violate the
condition imposed by INLA that observations be independent conditional on the latent variables. In this paper we
develop a flexible and scalable modelling framework for case-crossover models with linear and semi-parameteric effects
which retains the flexibility and computational advantages of INLA, but accomodates a broad class of models that
violate this conditional independence restriction. We apply our method to quantify non-linear associations between
mortality and extreme temperatures in India. An R package implementing our methods will be released publicly."

# Summary. An optional shortened abstract.
summary: "Non-linear associations between risk factors and mortality using data only from subjects who died."

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
