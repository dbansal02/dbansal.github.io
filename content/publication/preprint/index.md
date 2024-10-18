---
title: "Exact MCMC for intractable proposals"
authors: 'Dwija Kakkad, Dootika Vats'
date: "2024-10-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-10-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Accept-reject based Markov chain Monte Carlo (MCMC) methods are the workhorse algorithm for Bayesian inference. These algorithms, like Metropolis-Hastings, require the choice of a proposal distribution which is typically informed by the desired target distribution. Surprisingly, proposal distributions with unknown normalizing constants are not uncommon, even though for such a choice of a proposal, the Metropolis-Hastings acceptance ratio cannot be evaluated exactly. Across the literature, authors resort to approximation methods that yield inexact MCMC or develop specialized algorithms to combat this problem. We show how Bernoulli factory MCMC algorithms, originally proposed for doubly intractable target distributions, can quite naturally be adapted to this situation. We present three diverse and relevant examples demonstrating the usefulness of the Bernoulli factory approach to this problem.

# Summary. An optional shortened abstract.
summary: ''

tags:
- ''

featured: false

links:
# - name: ''
url: ''
url_pdf: https://arxiv.org/pdf/2410.10282
url_code: 'https://github.com/dwija04/BernoulliFactoryProposals'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs. -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
