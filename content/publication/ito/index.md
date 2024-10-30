---
publication_types: ['article-journal']
title: "Cosmic ray interstellar propagation tool using Itô Calculus (criptic): software for simultaneous calculation of cosmic ray transport and observational signatures"
authors: ["MR Krumholz", "RM Crocker", "ML Sampson"]
author_notes:
date: "2022-10-01T00:00:00Z"
url_pdf: 'https://arxiv.org/abs/2207.13838'
url_code: 'https://bitbucket.org/krumholz/criptic/src/master/'
publication: "*Monthly Notices of the Royal Astronomical Society 517 (1), 1355-1380*"
abstract: "We present criptic, the Cosmic Ray Interstellar Propagation Tool using Itô Calculus, a new open-source software package to simulate the propagation of cosmic rays through the interstellar medium and to calculate the resulting observable non-thermal emission. Criptic solves the Fokker-Planck equation describing transport of cosmic rays on scales larger than that on which their pitch angles become approximately isotropic, and couples this to a rich and accurate treatment of the microphysical processes by which cosmic rays in the energy range ∼MeV to ∼PeV lose energy and produce emission. Criptic is deliberately agnostic as to both the cosmic ray transport model and the state of the background plasma through which cosmic rays travel. It can solve problems where cosmic rays stream, diffuse, or perform arbitrary combinations of both, and the coefficients describing these transport processes can be arbitrary functions of the background plasma state, the properties of the cosmic rays themselves, and local integrals of the cosmic ray field itself (e.g., the local cosmic ray pressure or pressure gradient). The code is parallelised using a hybrid OpenMP-MPI paradigm, allowing rapid calculations exploiting multiple cores and nodes on modern supercomputers. Here we describe the numerical methods used in the code, our treatment of the microphysical processes, and the set of code tests and validations we have performed.
"
---



