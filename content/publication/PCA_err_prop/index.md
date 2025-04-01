---
title: "On the Error-Propagation of Inexact Hotelling's Deflation for Principal Component Analysis"
authors:
    - admin
    - J. Lyle Kim
    - Cruz Barnum
    - Anastasios Kyrillidis
date: "2024-07-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*International Conference on Machine Learning, 2024*"
publication_short: "ICML"

abstract: "Principal Component Analysis (PCA) aims to find
subspaces spanned by the so-called principal components that best represent the variance in the
dataset. The deflation method is a popular metaalgorithm that sequentially finds individual principal components, starting from the most important
ones and working towards the less important ones.
However, as deflation proceeds, numerical errors
from the imprecise estimation of principal components propagate due to its sequential nature.
This paper mathematically characterizes the error
propagation of the inexact Hotelling’s deflation
method. We consider two scenarios: i) when the
sub-routine for finding the leading eigenvector is
abstract and can represent various algorithms; and
ii) when power iteration is used as the sub-routine.
In the latter case, the additional directional information from power iteration allows us to obtain a
tighter error bound than the sub-routine agnostic
case. For both scenarios, we explicitly characterize how the errors progress and affect subsequent
principal component estimations."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Machine Learning Theory

featured: false

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/pdf/2310.04283

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
