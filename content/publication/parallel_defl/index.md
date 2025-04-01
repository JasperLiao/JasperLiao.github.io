---
title: "Provable Model-Parallel Distributed Principal Component Analysis with Parallel Deflation"
authors:
    - admin
    - Wenyi Su
    - Anastasios Kyrillidis
date: "2025-03-07T00:00:00Z"
doi: ""
reading_time: false
# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*Conference on Parsimony and Learning, 2025*"
publication_short: "CPAL"

abstract: 'We study a distributed Principal Component Analysis (PCA) framework where each worker targets a distinct eigenvector and refines its solution by updating from intermediate solutions provided by peers deemed as "superior". Drawing intuition from the deflation method in centralized eigenvalue problems, our approach breaks the sequential dependency in the deflation steps and allows asynchronous updates of workers, while incurring only a small communication cost. To our knowledge, a gap in the literature -- the theoretical underpinning of such distributed, dynamic interactions among workers -- has remained unaddressed. This paper offers a theoretical analysis explaining why, how, and when these intermediate, hierarchical updates lead to practical and provable convergence in distributed environments. Despite being a theoretical work, our prototype implementation demonstrates that such a distributed PCA algorithm converges effectively and in scalable way: through experiments, our proposed framework offers comparable performance to EigenGame-$\mu$
 , the state-of-the-art model-parallel PCA solver.'

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Distributed Learning

featured: true

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/pdf/2502.17615
url_code: https://github.com/JLiao980706/ParallelDeflation
url_poster: https://jasperliao.github.io/uploads/parallel_defl_poster.pdf

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

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

<!-- This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
