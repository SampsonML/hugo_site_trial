---
publication_types: ["article-journal"]
title: "Score-matching neural networks for improved multi-band source separation"
authors:
- ML Sampson, P Melchior, C Ward, S Birmingham
author_notes:
date: "2024-02-01T00:00:00Z"
url_pdf: 'www.arxiv.org/abs/2401.07313'
url_code: 'https://github.com/pmelchior/scarlet2'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.

# Publication name and optional abbreviated publication name.
#publication: "*Journal of Source Themes, 1*(1)"

#abstract: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac #convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. Sed ac faucibus dolor, #scelerisque sollicitudin nisi. Cras purus urna, suscipit quis sapien eu, pulvinar tempor diam. #Quisque risus orci, mollis id ante sit amet, gravida egestas nisl. Sed ac tempus magna. Proin in #dui enim. Donec condimentum, sem id dapibus fringilla, tellus enim condimentum arcu, nec volutpat #est felis vel metus. Vestibulum sit amet erat at nulla eleifend gravida.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis #placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#tags:
#- Source Themes
#featured: false

# links:
# - name: ""
#   url: ""
#url_pdf: http://arxiv.org/pdf/1512.04133v1
#url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
#url_dataset: ''
#url_poster: ''
#url_project: ''
#url_slides: ''
#url_source: ''
#url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

{{% callout note %}}
We present the implementation of a score-matching neural network that represents a data-driven prior for non-parametric galaxy morphologies. The gradients of this prior can be included in the optimization routine of the recently developed multi-band modeling framework Scarlet2, a redesign of the Scarlet method currently employed as deblender in the pipelines of the HyperSuprimeCam survey and the Rubin Observatory. The addition of the prior avoids the requirement of nondifferentiable constraints, which can lead to convergence failures we discovered in Scarlet. We present the architecture and training details of our score-matching neural network and show with simulated Rubin-like observations that Scarlet2 outperforms Scarlet in accuracy of total flux and morphology estimates, while maintaining excellent performance for colors. We also demonstrate significant improvements in the robustness to inaccurate initializations. Scarlet2 is written in python, extendend by JAX and equinox, and is fully GPU compatible. The implementation and data package of the score model are publicly available at this https URL.
{{% /callout %}}

