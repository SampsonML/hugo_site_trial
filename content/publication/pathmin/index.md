---
publication_types: ['article-journal']
title: "Path-minimizing Latent ODEs for improved extrapolation and inference -- MLST (full version) -- NeurIPS ML for Physical Sciences"
authors:
- ML Sampson, P Melchior
author_notes:
date: "2024-10-01T00:00:00Z"
url_pdf: 'https://arxiv.org/abs/2410.08923'


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
Latent ODE models provide flexible descriptions of dynamic systems, but they can struggle with extrapolation and predicting complicated non-linear dynamics. The latent ODE approach implicitly relies on encoders to identify unknown system parameters and initial conditions, whereas the evaluation times are known and directly provided to the ODE solver. This dichotomy can be exploited by encouraging time-independent latent representations. By replacing the common variational penalty in latent space with an ℓ2 penalty on the path length of each system, the models learn data representations that can easily be distinguished from those of systems with different configurations. This results in faster training, smaller models, more accurate interpolation and long-time extrapolation compared to the baseline ODE models with GRU, RNN, and LSTM encoder/decoders on tests with damped harmonic oscillator, self-gravitating fluid, and predator-prey systems. We also demonstrate superior results for simulation-based inference of the Lotka-Volterra parameters and initial conditions by using the latents as data summaries for a conditional normalizing flow. Our change to the training loss is agnostic to the specific recognition network used by the decoder and can therefore easily be adopted by other latent ODE models.
{{% /callout %}}
