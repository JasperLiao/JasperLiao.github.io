---
title: Strong Lottery Ticket Hypothesis with $\epilon$–perturbation
authors:
    - admin
    - Anastasios Kyrillidis
date: "2023-02-31T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

reading_time: false

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*International Conference on Artificial
Intelligence and Statistics, 2023*"
publication_short: "AISTATS"

abstract: "The strong Lottery Ticket Hypothesis (LTH) (Ramanujan et al., 2019; Zhou et al., 2019) claims
the existence of a subnetwork in a sufficiently
large, randomly initialized neural network that
approximates some target neural network without the need of training. We extend the theoretical guarantee of the strong LTH literature
to a scenario more similar to the original LTH,
by generalizing the weight change in the pretraining step to some perturbation around initialization. In particular, we focus on the following
open questions: By allowing an ε-scale perturbation on the random initial weights, can we reduce the over-parameterization requirement for
the candidate network in the strong LTH? Furthermore, does the weight change by SGD coincide with a good set of such perturbation?
We answer the first question by first extending
the theoretical result on the subset sum problem (Lueker, 1998) to allow perturbation on the
candidates. Applying this result to the neural network setting, we show that by allowing
ε-scale perturbation, we can reduce the overparameterization requirement of the strong LTH
by a factor of O(1/(1 + ε)). To answer the second question, we show via experiments that the
perturbed weight achieved by the projected SGD
shows better performance under the strong LTH
pruning."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Deep Learning Theory, Neural Network Pruning

featured: false

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://proceedings.mlr.press/v206/xiong23a/xiong23a.pdf

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
