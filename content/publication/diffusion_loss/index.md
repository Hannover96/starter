---
title: "Interpolating between BSDEs and PINNs – deep learning for elliptic and parabolic boundary value problems"
authors:
- N. Nüsken
- L. Richter
date: "2023-03-08T00:00:00Z"
doi: ""

show_related: false

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Journal of Machine Learning*
publication_short: In *JML*

abstract: Solving high-dimensional partial differential equations is a recurrent challenge in economics, science and engineering. In recent years, a great number of computational approaches have been developed, most of them relying on a combination of Monte Carlo sampling and deep learning based approximation. For elliptic and parabolic problems, existing methods can broadly be classified into those resting on reformulations in terms of *backward stochastic differential equations* (BSDEs) and those aiming to minimize a regression-type L2-error (*physics-informed neural networks*, PINNs). In this paper, we review the literature and suggest a methodology based on the novel diffusion loss that interpolates between BSDEs and PINNs. Our contribution opens the door towards a unified understanding of numerical approaches for high-dimensional PDEs, as well as for implementations that combine the strengths of BSDEs and PINNs. We also provide generalizations to eigenvalue problems and perform extensive numerical studies, including calculations of the ground state for nonlinear Schrödinger operators and committor functions relevant in molecular dynamics.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
#- Source Themes
featured: false

links:
- name: arxiv
url: https://arxiv.org/pdf/2112.03749.pdf
  url_pdf: https://www.jml.pub/intro/article_detail/jml/21512.html#
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
