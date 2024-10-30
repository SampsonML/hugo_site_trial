---
publication_types: ['article-journal']
title: "Cosmic ray interstellar propagation tool using Itô Calculus (criptic): software for simultaneous calculation of cosmic ray transport and observational signatures -- MNRAS"
authors:
- MR Krumholz, RM Crocker, ML Sampson
author_notes:
date: "2022-10-01T00:00:00Z"
url_pdf: 'https://arxiv.org/abs/2207.13838'
url_code: 'https://bitbucket.org/krumholz/criptic/src/master/'


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
We present criptic, the Cosmic Ray Interstellar Propagation Tool using Itô Calculus, a new open-source software package to simulate the propagation of cosmic rays through the interstellar medium and to calculate the resulting observable non-thermal emission. Criptic solves the Fokker-Planck equation describing transport of cosmic rays on scales larger than that on which their pitch angles become approximately isotropic, and couples this to a rich and accurate treatment of the microphysical processes by which cosmic rays in the energy range ∼MeV to ∼PeV lose energy and produce emission. Criptic is deliberately agnostic as to both the cosmic ray transport model and the state of the background plasma through which cosmic rays travel. It can solve problems where cosmic rays stream, diffuse, or perform arbitrary combinations of both, and the coefficients describing these transport processes can be arbitrary functions of the background plasma state, the properties of the cosmic rays themselves, and local integrals of the cosmic ray field itself (e.g., the local cosmic ray pressure or pressure gradient). The code is parallelised using a hybrid OpenMP-MPI paradigm, allowing rapid calculations exploiting multiple cores and nodes on modern supercomputers. Here we describe the numerical methods used in the code, our treatment of the microphysical processes, and the set of code tests and validations we have performed.
{{% /callout %}}
