---
title: "Provable Accelerated Convergence of Nesterov’s Momentum for Deep ReLU Neural Networks"
authors:
    - admin
    - Anastasios Kyrillidis
date: "2024-03-01T00:00:00Z"
doi: ""

reading_time: false

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*International Conference on Algorithmic Learning Theory, 2024*"
publication_short: "TMLR"

abstract: "Current state-of-the-art analyses on the convergence of gradient descent for training neural networks focus on characterizing properties of the loss landscape, such as the Polyak-Łojaciewicz
(PL) condition and the restricted strong convexity. While gradient descent converges linearly under such conditions, it remains an open question whether Nesterov’s momentum enjoys accelerated
convergence under similar settings and assumptions. In this work, we consider a new class of objective functions, where only a subset of the parameters satisfies strong convexity, and show Nesterov’s
momentum achieves acceleration in theory for this objective class. We provide two realizations of
the problem class, one of which is deep ReLU networks, which constitutes this work as the first
that proves an accelerated convergence rate for non-trivial neural network architectures."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Deep Learning Theory

featured: true

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://proceedings.mlr.press/v237/liao24a/liao24a.pdf

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
