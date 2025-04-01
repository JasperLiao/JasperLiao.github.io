---
title: "On the Convergence of Shallow Neural Network Training with Randomly Masked Neurons"
authors:
    - admin
    - Anastasios Kyrillidis
date: "2022-06-05T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Transactions on Machine Learning, 2022*"
publication_short: "TMLR"

reading_time: false

abstract: "With the motive of training all the parameters of a neural network, we study why and when one can achieve this by iteratively creating, training, and combining randomly selected subnetworks. Such scenarios have either implicitly or explicitly emerged in the recent literature: see e.g., the Dropout family of regularization techniques, or some distributed ML training protocols that reduce communication/computation complexities, such as the Independent Subnet Training protocol. While these methods are studied empirically and utilized in practice, they often enjoy partial or no theoretical support, especially when applied on neural network-based objectives.\n

In this manuscript, our focus is on overparameterized single hidden layer neural networks with ReLU activations in the lazy training regime. By carefully analyzing i) the subnetworks’ neural tangent kernel, ii) the surrogate functions’ gradient, and iii) how we sample and combine the surrogate functions, we prove linear convergence rate of the training error –up to a neighborhood around the optimal point– for an overparameterized single-hidden layer perceptron with a regression loss. Our analysis reveals a dependency of the size of the neighborhood around the optimal point on the number of surrogate models and the number of local training steps for each selected subnetwork. Moreover, the considered framework generalizes and provides new insights on dropout training, multi-sample dropout training, as well as Independent Subnet Training; for each case, we provide convergence results as corollaries of our main theorem."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Deep Learning Theory

featured: false

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/pdf/2112.02668
url_code: 'https://github.com/HugoBlox/hugo-blox-builder'

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
