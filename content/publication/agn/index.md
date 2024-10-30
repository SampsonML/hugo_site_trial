---
publication_types: ['article-journal']
title: "Disentangling transients and their host galaxies with Scarlet2: A framework to forward model multi-epoch imaging"
authors:
- C Ward, P Melchior, ML Sampson, C Burke, J Siegel, B Remy, S Birmingham, E Ramey, S van Velzen
author_notes:
date: "2024-09-01T00:00:00Z"
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
Many science cases for wide-field time-domain surveys rely on accurate identification and characterization of the galaxies hosting transient and variable objects. In the era of the Legacy Survey of Space and Time (LSST) at the Vera C. Rubin Observatory the number of known transient and variable sources will grow by orders of magnitude, and many of these sources will be blended with their host galaxies and neighboring galaxies. A diverse range of applications - including the classification of nuclear and non-nuclear sources, identification of potential host galaxies, extraction of host galaxy SEDs without requiring a transient-free reference image, and combined analysis of photometry from multiple surveys - will benefit from a flexible framework to model time-domain imaging of transients. We describe a time-domain extension of the Scarlet2 scene modeling code for multi-epoch, multi-band, and multi-resolution imaging data to extract simultaneous transient and host galaxy models. Scarlet2 leverages the benefits of data-driven priors on galaxy morphology, is fully GPU compatible, and can jointly model multi-resolution data from ground and space-based surveys. We demonstrate the method on simulated LSST-like supernova imaging, low-resolution Zwicky Transient Facility imaging of tidal disruption events, and Hyper Suprime Cam imaging of variable AGN out to z = 4 in the COSMOS fields. We show that Scarlet2 models provide accurate transient and host galaxy models as well as accurate measurement of host-transient spatial offsets, and demonstrate future applications to the search for 'wandering' massive black holes.
{{% /callout %}}
