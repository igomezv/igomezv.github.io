---
layout: page
title: Code
---

You can visit my [GitHub profile](https://github.com/igomezv) to explore additional projects, as well as materials from tutorials, courses, and workshops.

- [doppleriann](#doppleriann)
- [SimpleMC](#simplemc)
- [nnogada](#nnogada)
- [neuralike](#neuralike)
- [Cosmo Reconstructions](#ann-reconstructions)
- [NCosmoVAE](#ncosmovae)

---

### doppleriann

**Doppler-shift Inference with Artificial Neural Networks (DopplerIANN)**

`doppleriann` is Python package for modeling Doppler shifts in high-resolution stellar spectra using physically motivated spectral-shell representations and deep learning. It contains the methodological framework presented in our paper: [doi.org/10.1051/0004-6361/202659375](https://doi.org/10.1051/0004-6361/202659375).

- Library GitHub repository: [igomezv/doppleriann](https://github.com/igomezv/doppleriann)
- Docs: [doppleriann/Docs](https://igomezv.github.io/doppleriann/)

![Figura](https://igomezv.github.io/assets/img/doppleriann_workflow.png){: .mx-auto.d-block :}
![Figura](https://igomezv.github.io/assets/img/doppleriann_periodogram.png){: .mx-auto.d-block :}

### SimpleMC

**Cosmological parameter inference toolkit for Bayesian analysis and statistical sampling.**

`SimpleMC` is a cosmological parameter estimation framework originally developed by Dr. A. Slosar and Dr. J. A. Vázquez. Between **2019 and 2023**, I contributed to the development and maintenance of the codebase, including nested sampling implementations, convergence criteria for Metropolis–Hastings algorithms, post-processing utilities, and additional analysis modules.

**Links**

- Library GitHub repository: [ja-vazquez/SimpleMC](https://github.com/ja-vazquez/SimpleMC)  
- Documentation: [igomezv/SimpleMC/Docs](https://igomezv.github.io/SimpleMC)  
- Workshop/tutorial: [igomezv/simplemc_workshop](https://github.com/igomezv/simplemc_workshop)  

![Figura](https://igomezv.github.io/assets/img/triangleSimplemc.png){: .mx-auto.d-block :}

---

### nnogada

**Neural networks optimized with genetic algorithms for data-driven inference and reconstruction.**

`nnogada` (**Neural Networks Optimized by Genetic Algorithms in Data Analysis**) is a framework combining neural networks and genetic algorithms for flexible modeling, reconstruction, and parameter inference in astrophysical and cosmological applications.

**Links**

- Library GitHub repository: [igomezv/nnogada](https://github.com/igomezv/nnogada)  
- Documentation: [docs/nnogada](https://igomezv.github.io/nnogada)  

![Figura](https://raw.githubusercontent.com/igomezv/igomezv.github.io/main/assets/img/nnogada.png){: .mx-auto.d-block :}

**Projects using `nnogada`**

- [igomezv/Reconstructing-RC-with-ANN](https://github.com/igomezv/Reconstructing-RC-with-ANN)  
- [igomezv/LSST_DE_neural_reconstruction](https://github.com/igomezv/LSST_DE_neural_reconstruction)  
- [igomezv/neuralike](https://github.com/igomezv/neuralike)  

---

### neuralike

**Bayesian inference for accelerating cosmological likelihood evaluations.**

`neuralike` implements deep-learning surrogate models combined with genetic-algorithm optimization to accelerate Bayesian inference workflows in cosmology, particularly for computationally expensive likelihood evaluations within sampling pipelines.

**Links**

- Library GitHub repository: [igomezv/neuralike](https://github.com/igomezv/neuralike)  
- Integration with `SimpleMC` and nested sampling using `dynesty`: [igomezv/simplemc_tests](https://github.com/igomezv/simplemc_tests/tree/neuralike)  

![Figura](https://raw.githubusercontent.com/igomezv/igomezv.github.io/main/assets/img/neuralike.png){: .mx-auto.d-block :}

---

### ANN Reconstructions

**Neural-network cosmological reconstructions with uncertainty quantification.**

Collection of Python implementations for model-independent reconstruction of cosmological observables using artificial neural networks, Monte Carlo Dropout uncertainty estimation, and hyperparameter optimization techniques.

<div style="display:flex; justify-content:center; gap:15px; flex-wrap:wrap;">
  <img src="https://igomezv.github.io/assets/img/rec1.png" style="width:48%; height:auto;" />
  <img src="https://igomezv.github.io/assets/img/rec2.png" style="width:48%; height:auto;" />
</div>

**Repositories**

- Unified reconstruction library: [igomezv/alp](https://github.com/igomezv/alp)
- Galaxy rotation curves: [igomezv/Reconstructing-RC-with-ANN](https://github.com/igomezv/Reconstructing-RC-with-ANN)
- LSST supernova simulations: [igomezv/LSST_DE_neural_reconstruction](https://github.com/igomezv/LSST_DE_neural_reconstruction)
- Cosmological observables reconstruction: [igomezv/neuralCosmoReconstruction](https://github.com/igomezv/neuralCosmoReconstruction)

---

## NCosmoVAE

**Variational autoencoders for fast generative modeling of cosmological N-body simulations.**

Variational autoencoder framework trained on **N-body cosmological simulations** to generate realistic dark matter halo realizations. Hyperparameter optimization with genetic algorithms using the `optuna` Python library.

**Links**

- Library repository: [igomezv/NcosmoVAE](https://github.com/igomezv/NcosmoVAE)  
- Related: [PRD paper.](https://arxiv.org/abs/2507.18054)

![Figura](https://igomezv.github.io/assets/img/Nbody.png){: .mx-auto.d-block :}
