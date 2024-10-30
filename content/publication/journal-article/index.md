---
publication_types: ["article-journal"]
title: "Score-matching neural networks for improved multi-band source separation. Astronomy and Computing"
authors: [ML Sampson, P Melchior, C Ward, S Birmingham]
author_notes:
date: "2024-02-01T00:00:00Z"
url_pdf: 'www.arxiv.org/abs/2401.07313'
url_code: 'https://github.com/pmelchior/scarlet2'
publication: "*Astronomy and Computing*"
abstract: "We present the implementation of a score-matching neural network that represents a data-driven prior for non-parametric galaxy morphologies. The gradients of this prior can be included in the optimization routine of the recently developed multi-band modeling framework Scarlet2, a redesign of the Scarlet method currently employed as deblender in the pipelines of the HyperSuprimeCam survey and the Rubin Observatory. The addition of the prior avoids the requirement of nondifferentiable constraints, which can lead to convergence failures we discovered in Scarlet. We present the architecture and training details of our score-matching neural network and show with simulated Rubin-like observations that Scarlet2 outperforms Scarlet in accuracy of total flux and morphology estimates, while maintaining excellent performance for colors. We also demonstrate significant improvements in the robustness to inaccurate initializations. Scarlet2 is written in python, extendend by JAX and equinox, and is fully GPU compatible. The implementation and data package of the score model are publicly available at this https URL."
---


