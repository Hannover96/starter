---
title: "Bayesian Learning via Neural Schrödinger-Föllmer Flows"
authors:
- A. Garbuno-Inigo
- N. Nüsken
- S. Reich
date: "2020-04-29T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *SIAM Journal on Applied Dynamical Systems*
publication_short: In *SIAM J. Appl. Dyn. Syst.*

abstract: We propose a computational method (with acronym ALDI) for sampling from a given target distribution based on first-order (overdamped) Langevin dynamics which satisfies the property of affine invariance. The central idea of ALDI is to run an ensemble of particles with their empirical covariance serving as a preconditioner for their underlying Langevin dynamics. ALDI does not require taking the inverse or square root of the empirical covariance matrix, which enables application to high-dimensional sampling problems. The theoretical properties of ALDI are studied in terms of nondegeneracy and ergodicity. Furthermore, we study its connections to diffusion on Riemannian manifolds and Wasserstein gradient flows. Bayesian inference serves as a main application area for ALDI. In case of a forward problem with additive Gaussian measurement errors, ALDI allows for a gradient-free approximation in the spirit of the ensemble Kalman filter. A computational comparison between gradient-free and gradient-based ALDI is provided for a PDE constrained Bayesian inverse problem.


Read More: https://epubs.siam.org/doi/abs/10.1137/19M1304891

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
#- Source Themes
featured: false

links:
- name: arxiv
  url: https://arxiv.org/pdf/1912.02859.pdf
url_pdf: https://epubs.siam.org/doi/pdf/10.1137/19M1304891
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
