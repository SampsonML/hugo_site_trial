---
publication_types: ['paper-conference']
title: "Spotting Hallucinations in Inverse Problems with Data-Driven Priors"
authors: [ML Sampson, P Melchior]
author_notes:
date: "2023-08-01T00:00:00Z"
url_pdf: 'https://arxiv.org/abs/2306.13272'
url_code: 'https://github.com/SampsonML/hallucination_score/tree/main'
url_video: 'https://icml.cc/virtual/2023/28195'
publication: "**Spotlight talk** *at Machine Learning for Astrophysics. Workshop at the Fortieth International Conference on Machine Learning (ICML 2023), July 29th, Hawaii, USA.*"
abstract: "Hallucinations are an inescapable consequence of solving inverse problems with deep neural networks. The expressiveness of recent generative models is the reason why they can yield results far superior to conventional regularizers; it can also lead to realistic-looking but incorrect features, potentially undermining the trust in important aspects of the reconstruction. We present a practical and computationally efficient method to determine, which regions in the solutions of inverse problems with data-driven priors are prone to hallucinations. By computing the diagonal elements of the Fisher information matrix of the likelihood and the data-driven prior separately, we can flag regions where the information is prior-dominated. Our diagnostic can directly be compared to the reconstructed solutions and enables users to decide if measurements in such regions are robust for their application. Our method scales linearly with the number of parameters and is thus applicable in high-dimensional settings, allowing it to be rolled out broadly for the large-volume data products of future wide-field surveys."
---

