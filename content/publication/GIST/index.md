---
title: "GIST: Distributed Training for Large-Scale Graph Convolutional Networks"
authors:
    - Cameron R. Wolfe
    - Jingkang Yang
    - admin
    - Arindam Chowdhury
    - Chen Dun
    - Artun Bayer
    - Santiago Segarra
    - Anastasios Kyrillidis
date: "2023-02-07T00:00:00Z"
doi: ""

author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'

reading_time: false
# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Applied and Computational Topology, 2023*"
publication_short: ''

abstract: "The graph convolutional network (GCN) is a goto solution for machine learning on graphs, but
its training is notoriously difficult to scale both
in terms of graph size and the number of model
parameters. Although some work has explored
training on large-scale graphs (e.g., GraphSAGE,
ClusterGCN, etc.), we pioneer efficient training
of large-scale GCN models (i.e., ultra-wide, overparameterized models) with the proposal of a
novel, distributed training framework. Our proposed training methodology, called GIST, disjointly partitions the parameters of a GCN model
into several, smaller sub-GCNs that are trained
independently and in parallel. In addition to being compatible with all GCN architectures and
existing sampling techniques for efficient GCN
training, GIST i) improves model performance,
ii) scales to training on arbitrarily large graphs,
iii) decreases wall-clock training time, and iv) enables the training of markedly overparameterized
GCN models. Remarkably, with GIST, we train
an astonishgly-wide 32,768-dimensional GraphSAGE model, which exceeds the capacity of a
single GPU by a factor of 8×, to SOTA performance on the Amazon2M dataset."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Distributed Learning

featured: false

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/pdf/2102.10424

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
