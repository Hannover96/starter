---
title: "VarGrad: A Low-Variance Gradient Estimator for Variational Inference"
authors:
- admin
- Robert Ford
date: "2013-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Source Themes Conference*
publication_short: In *STC*

abstract: We analyse the properties of an unbiased gradient estimator of the evidence lower
bound (ELBO) for variational inference, based on the score function method with
leave-one-out control variates. We show that this gradient estimator can be obtained
using a new loss, defined as the variance of the log-ratio between the exact posterior
and the variational approximation, which we call the $log-variance loss$. Under
certain conditions, the gradient of the log-variance loss equals the gradient of the
(negative) ELBO. We show theoretically that this gradient estimator, which we call
VarGrad due to its connection to the log-variance loss, exhibits lower variance than
the score function method in certain settings, and that the leave-one-out control
variate coefficients are close to the optimal ones. We empirically demonstrate that
VarGrad offers a favourable variance versus computation trade-off compared to
other state-of-the-art estimators on a discrete variational autoencoder (VAE).

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

links:
- name: Custom Link
  url: http://example.org
url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
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
