---
publication_types: ['paper-conference']
title: "Spotting Hallucinations in Inverse Problems with Data-Driven Priors *ICML Workshop Spotlight Talk*"
authors:
- ML Sampson, P Melchior
author_notes:
date: "2023-08-01T00:00:00Z"
url_pdf: 'https://arxiv.org/abs/2306.13272'
url_code: 'https://github.com/SampsonML/hallucination_score/tree/main'
url_video: 'https://icml.cc/virtual/2023/28195'


# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
#publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
#publication: "*Journal of Source Themes, 1*(1)"
#publication_short: ""

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
Hallucinations are an inescapable consequence of solving inverse problems with deep neural networks. The expressiveness of recent generative models is the reason why they can yield results far superior to conventional regularizers; it can also lead to realistic-looking but incorrect features, potentially undermining the trust in important aspects of the reconstruction. We present a practical and computationally efficient method to determine, which regions in the solutions of inverse problems with data-driven priors are prone to hallucinations. By computing the diagonal elements of the Fisher information matrix of the likelihood and the data-driven prior separately, we can flag regions where the information is prior-dominated. Our diagnostic can directly be compared to the reconstructed solutions and enables users to decide if measurements in such regions are robust for their application. Our method scales linearly with the number of parameters and is thus applicable in high-dimensional settings, allowing it to be rolled out broadly for the large-volume data products of future wide-field surveys.
{{% /callout %}}
