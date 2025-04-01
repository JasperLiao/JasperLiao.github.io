---
title: "Scissorhands: Exploiting the Persistence of Importance Hypothesis for LLM KV Cache Compression at Test Time"
authors:
    - Zichang Liu
    - Aditya Desai
    - admin
    - Weitao Wang
    - Victor Xie
    - Zhaozhuo Xu
    - Anastasios Kyrillidis
    - Anshumali Shrivastava
date: "2023-12-07T00:00:00Z"
doi: ""

reading_time: false

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*Conference on Neural Information Processing Systems, 2023*"
publication_short: "NeurIPS"

abstract: "Large language models(LLMs) have sparked a new wave of exciting AI applications. Hosting these models at scale requires significant memory resources. One
crucial memory bottleneck for the deployment stems from the context window. It is
commonly recognized that model weights are memory hungry; however, the size of
key-value embedding stored during the generation process (KV cache) can easily
surpass the model size. The enormous size of the KV cache puts constraints on
the inference batch size, which is crucial for high throughput inference workload.
Inspired by an interesting observation of the attention scores, we hypothesize the
persistence of importance: only pivotal tokens, which had a substantial influence
at one step, will significantly influence future generations. Based on our empirical
verification and theoretical analysis around this hypothesis, we propose SCISSORHANDS, a system that maintains the memory usage of KV cache under a fixed
budget without finetuning the model. We validate that SCISSORHANDS reduces
the inference memory usage of the KV cache by up to 5× without compromising
model quality. We further demonstrate that SCISSORHANDS can be combined with
4-bit quantization for further compression"

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Efficient Inference Algorithm

featured: false

# links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://proceedings.neurips.cc/paper_files/paper/2023/file/a452a7c6c463e4ae8fbdc614c6e983e6-Paper-Conference.pdf

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
