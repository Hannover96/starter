---
title: "Topics in sampling schemes based on Markov processes"
authors:
- N. Nüsken
date: "2018-05-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: PhD thesis
publication_short: PhD thesis

abstract: 	In this thesis we consider several topics related to the construction of optimal Markovian dynamics in the context of sampling from high-dimensional probability distributions. Firstly, we introduce and analyse Langevin samplers that consist of perturbations of the standard overdamped and underdamped Langevin dynamics. The perturbed dynamics is such that its invariant measure is the same as that of the unperturbed dynamics. We show that appropriate choices of the perturbations can lead to samplers that have improved properties, at least in terms of reducing the asymptotic variance. We present a detailed analysis of the new Langevin samplers for Gaussian target distributions. Our theoretical results are supported by numerical experiments with non-Gaussian target measures. Secondly, we present a general framework for the analysis and development of ensemble based methods, encompassing both diﬀusion and piecewise deterministic Markov processes. For many performance criteria of interest, including the asymptotic variance, the task of ﬁnding efficient couplings can be phrased in terms of problems related to the theory of optimal transportation. We investigate general structural properties, proving a singularity theorem that has both geometric and probabilistic interpretations. Moreover, we show that those problems can often be solved approximately and support our findings with numerical experiments. Addressing the convergence to equilibrium of coupled processes we furthermore derive a modiﬁed Poincaré inequality. Finally, under some conditions, we prove exponential ergodicity for the zigzag process using hypocoercivity techniques.


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
