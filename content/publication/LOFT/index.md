---
title: "LoFT: Finding Lottery Tickets through Filter-wise Training"
authors:
    - Qihan Wang
    - Chen Dun
    - admin
    - Chris Jermaine
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
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*International Conference on Artificial Intelligence and Statistics, 2022*"
publication_short: "AISTATS"

abstract: 'Recent work on the Lottery Ticket Hypothesis (LTH) shows that there exist "**winning tickets**" in large neural networks. These tickets represent "sparse" versions of the full model that can be trained independently to achieve comparable accuracy with respect to the full model. However, finding the winning tickets requires one to pretrain the large model for at least a number of epochs, which can be a burdensome task, especially when the original neural network gets larger.
In this paper, we explore how one can efficiently identify the emergence of such winning tickets, and use this observation to design efficient pretraining algorithms. For clarity of exposition, our focus is on convolutional neural networks (CNNs). To identify good filters, we propose a novel filter distance metric that well-represents the model convergence. As our theory dictates, our filter analysis behaves consistently with recent findings of neural network learning dynamics. Motivated by these observations, we present the LOttery ticket through Filter-wise Training algorithm, dubbed as LoFT. LoFT is a model-parallel pretraining algorithm that partitions convolutional layers by filters to train them independently in a distributed setting, resulting in reduced memory and communication costs during pretraining. Experiments show that LoFT i) preserves and finds good lottery tickets, while ii) it achieves non-trivial computation and communication savings, and maintains comparable or even better accuracy than other pretraining methods.'

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Neural Network Pruning, Distributed Learning

featured: false

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/pdf/2210.16169

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
