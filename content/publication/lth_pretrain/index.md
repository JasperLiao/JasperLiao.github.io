---
title: "How Much Pre-training Is Enough to Discover a Good Subnetwork?"
authors:
    - Cameron R. Wolfe
    - admin
    - Qihan Wang
    - J. Lyle Kim
    - Anastasios Kyrillidis
date: "2024-02-23T00:00:00Z"
doi: ""

author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Transactions on Machine Learning, 2024*"
publication_short: "TMLR"

abstract: "Neural network pruning is useful for discovering efficient, high-performing subnetworks within pre-trained, dense network architectures. More often than not, it involves a three-step process—pretraining, pruning, and re-training—that is computationally expensive, as the dense model must
be fully pre-trained. While previous work has revealed through experiments the relationship between the amount of pre-training and the performance of the pruned network, a theoretical characterization of such dependency is still missing. Aiming to mathematically analyze the
amount of dense network pre-training needed for a pruned network to perform well, we discover a simple theoretical bound in the number of gradient descent pre-training iterations on a twolayer, fully-connected network, beyond which pruning via greedy forward selection [61] yields
a subnetwork that achieves good training error. Interestingly, this threshold is shown to be
logarithmically dependent upon the size of the dataset, meaning that experiments with larger
datasets require more pre-training for subnetworks obtained via pruning to perform well. Lastly,
we empirically validate our theoretical results on a multi-layer perceptron trained on MNIST."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Deep Learning Theory, Neural Network Pruning

featured: false

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/pdf/2108.00259

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
