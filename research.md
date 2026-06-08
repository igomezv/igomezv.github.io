---
layout: page
title: Research

---

Research focused on the intersection of deep learning, Bayesian inference, and astrophysics, with applications to cosmology, exoplanets, and stellar activity.

- [Selected publications](#selected-publications)| [Full list](https://igomezv.github.io/full_papers/)
- [Research software](#research-software)| [Full code contributions](https://github.com/igomezv)
- [Selected presentations](#selected-presentations)| [Full list](https://igomezv.github.io/full_presentations/)
- [Scientific service](#scientific-service)

-----

## Selected publications

Selected publications. For a complete publication list, see [<u>here</u>](https://igomezv.github.io/full_papers/) or the following profiles:

| [<u>ADS</u>](https://ui.adsabs.harvard.edu/search?q=author:"Gómez-Vargas, Isidro"&sort=date%20desc) | [<u>Google Scholar</u>](https://scholar.google.com.mx/citations?user=c9OLfMcAAAAJ&hl=es) | [<u>ORCID</u>](https://orcid.org/0000-0002-6473-018X) | [<u>ResearchGate</u>](https://www.researchgate.net/profile/Isidro-Gomez-Vargas) | [<u>arXiv</u>](https://arxiv.org/search/?searchtype=author&query=G%C3%B3mez-Vargas%2C+I) |
<br>

### Lead and co-lead

- [Chacón-Lavanderos, J., **Gómez-Vargas, I.**, Menchaca-Mendez, R., & Vázquez, J. A. (2026). Variational autoencoder for generating realistic N-body simulations for dark matter halos. Physical Review D. 113(6), 063520.](https://journals.aps.org/prd/abstract/10.1103/b6lj-rlff) <br>
**Contribution:** Co-lead author. Co-developed the methodological framework and manuscript preparation; developed the associated [code repository](https://github.com/igomezv/NcosmoVAE); supervised the first author (PhD student); corresponding author.

- [Garcia-Arroyo, G., **Gómez-Vargas, I.**, & Vázquez, J. A. (2026). Data-driven modeling of rotation curves with artificial neural networks. <i>Physics of the Dark Universe</i>, 52, 102240.](https://www.sciencedirect.com/science/article/pii/S2212686426000294) <br>
**Contribution:** Co-lead author and corresponding author. Developed the methodology, implementation, and data analysis; developed the associated [code repository](https://github.com/igomezv/Reconstructing-RC-with-ANN).

- [**Gómez-Vargas, I.**, & Vázquez, J. A. (2024). Deep learning and genetic algorithms for cosmological Bayesian inference speed-up. Physical Review D. 110(8), 083518.](https://arxiv.org/abs/2405.03293) <br>
**Contribution:** Lead author. Developed the inference framework, methodology, implementation, and data analysis; developed the associated [code repository](https://github.com/igomezv/nnogada).

- [Mitra, A., **Gómez-Vargas, I.**, & Zarikas, V. (2024). Dark energy reconstruction analysis with artificial neural networks: Application on simulated Supernova Ia data from Rubin Observatory. <i>Physics of the Dark Universe</i>, 46, 101706.](https://www.sciencedirect.com/science/article/pii/S2212686424002887) <br>
**Contribution:** Co-lead author and corresponding author. Led the methodological development, implementation, and analysis; developed the associated [code repository](https://github.com/igomezv/LSST_DE_neural_reconstruction).

- [**Gómez-Vargas, I.**, Andrade, J. B., & Vázquez, J. A. (2023). Neural networks optimized by genetic algorithms in cosmology. Physical Review D. 107(4), 043509.](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.107.043509) <br>
**Contribution:** Lead author. Developed the methodology, implementation, and analysis; developed the associated [code repository](https://github.com/igomezv/nnogada).

- [**Gómez-Vargas, I.**, Vázquez, J. A., Esquivel, R. M., & García-Salcedo, R. (2023). Neural network reconstructions for the Hubble parameter, growth rate and distance modulus. European Physical Journal C. 83(4), 304.](https://doi.org/10.1140/epjc/s10052-023-11435-9) <br>
**Contribution:** Lead author. Developed the reconstruction methodology and implementation; developed the associated [code repository](https://github.com/igomezv/neuralCosmoReconstruction).


### Selected collaborations

- [Di Valentino, E., et al. (including **Gómez-Vargas, I.**) (2025). The CosmoVerse White Paper: Addressing observational tensions in cosmology with systematics and fundamental physics. <i>Physics of the Dark Universe</i>, 101965.](https://www.sciencedirect.com/science/article/pii/S221268642500158X) <br>
**Contribution:** Contributed to the sections on reconstruction techniques and bioinspired algorithms for model selection, including material related to neural-network reconstruction.

- [Zhao, Y., Dumusque, X., Cretignier, M., Cameron, A. C., Latham, D. W., López-Morales, M., Mayor, M., Sozzetti, A., Cosentino, R., **Gómez-Vargas, I.**, Pepe, F., & Udry, S. (2024). Improving Earth-like planet detection in radial velocity using deep learning. Astronomy & Astrophysics. 687, A281.](https://doi.org/10.1051/0004-6361/202450022) <br>
**Contribution:** Contributed to manuscript review and methodological discussion of neural-network approaches for exoplanet detection.

- [Tamayo, D., Urquilla, E., & **Gómez-Vargas, I.** (2025). Equivalence of dark energy models: A theoretical and Bayesian perspective. <i>Physics of the Dark Universe</i>, 48, 101901.](https://doi.org/10.1016/j.dark.2025.101901) <br>
**Contribution:** Corresponding author. Led the Bayesian statistical analysis and contributed to manuscript preparation and scientific review.

-----
## Selected research software

---

Additional projects and software repositories are available on my [GitHub profile](https://github.com/igomezv).

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

![Figura](https://raw.githubusercontent.com/igomezv/igomezv.github.io/master/assets/img/nnogada.png){: .mx-auto.d-block :}

**Projects using `nnogada`**

- [igomezv/Reconstructing-RC-with-ANN](https://github.com/igomezv/Reconstructing-RC-with-ANN)  
- [igomezv/LSST_DE_neural_reconstruction](https://github.com/igomezv/LSST_DE_neural_reconstruction)  
- [igomezv/neuralike](https://github.com/igomezv/neuralike)  

---

### neuralike

**Surrogate-assisted Bayesian inference for accelerating cosmological likelihood evaluations.**

`neuralike` implements deep-learning surrogate models combined with genetic-algorithm optimization to accelerate Bayesian inference workflows in cosmology, particularly for computationally expensive likelihood evaluations within sampling pipelines.

**Links**

- Library GitHub repository: [igomezv/neuralike](https://github.com/igomezv/neuralike)  
- Integration with `SimpleMC` and nested sampling using `dynesty`: [igomezv/simplemc_tests](https://github.com/igomezv/simplemc_tests/tree/neuralike)  

![Figura](https://raw.githubusercontent.com/igomezv/igomezv.github.io/master/assets/img/neuralike.png){: .mx-auto.d-block :}

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

### NCosmoVAE

**Variational autoencoders for generative modeling of cosmological N-body simulations.**

`NCosmoVAE` is a variational autoencoder framework trained on cosmological N-body simulations to generate realistic dark matter halo realizations. The project incorporates hyperparameter optimization using genetic algorithms with the `optuna` Python library.

**Links**

- Library repository: [igomezv/NcosmoVAE](https://github.com/igomezv/NcosmoVAE)

![Figura](https://igomezv.github.io/assets/img/Nbody.png){: .mx-auto.d-block :}


-----
## Selected presentations
-----

Selected invited talks, conference presentations, and seminars.
Complete list: [<u>here</u>](https://igomezv.github.io/full_presentations/).

- **2026**
	- [Seminar] [*Deep learning for small astrophysical datasets: from cosmology to exoplanet detection*.](https://www.iaa.csic.es/evento/deep-learning-for-small-astrophysical-datasets-from-cosmology-to-exoplanet-detection/) Institutional seminar, Instituto de Astrofísica de Andalucía (IAA-CSIC), Granada, Spain. [On-site].
- **2025**
	- [Conference] [*Deep Learning strategies for detecting Earth-size exoplanets in HARPS-N stellar spectra*.](https://meetingorganizer.copernicus.org/EPSC-DPS2025/EPSC-DPS2025-270.html), EPSC-DPS 2025, Helsinki, Finland. [On-site].
	- [Conference] [*Reaching the 10 cm/s planetary detection limit on HARPS-N solar data using deep learning*.](https://www.iastro.pt/research/conferences/eprv6/EPRV6-programme.pdf) The Sixth Workshop on Extremely Precise Radial Velocities (EPRV 6), Porto, Portugal. [On-site].
	- [Seminar] [*Machine learning for small astrophysical datasets: applications in cosmology and exoplanets*.](https://www.youtube.com/watch?v=4C8xfMJwTZE&t=114s) Pizza Seminar, Instituto de Ciencias del Espacio (ICE-CSIC), Barcelona, Spain. [On-site].
	- [Conference] *Deep learning for small astrophysical datasets: applications in cosmology and exoplanets*. ICGCAS-2025, PICS, Odisha, India. [Online].
- **2024**
	- [Seminar] *Machine Learning for Astrophysical Data Analysis and Stellar Spectra Modeling*, Exoplanet Group Seminar, University of Geneva, Geneva, Switzerland. [On-site].
	- [Talk] *Aceleración de la Inferencia Bayesiana mediante Redes Neuronales y Algoritmos Genéticos*, III Mini Workshop on HPC in Science and Engineering, ICF-UNAM, Cuernavaca, México. [Online].


-----

## Scientific service

-----

### Journal peer review

- [Physical Review D](https://journals.aps.org/prd/)
- [IEEE Transactions on Pattern Analysis and Machine Intelligence](https://ieeexplore.ieee.org/xpl/aboutJournal.jsp?punumber=34)
- [Journal of Cosmology and Astroparticle Physics](https://iopscience.iop.org/journal/1475-7516)
- [Physics of the Dark Universe](https://www.sciencedirect.com/journal/physics-of-the-dark-universe)
- [European Physical Journal C](https://link.springer.com/journal/10052)
- [Indian Journal of Physics](https://link.springer.com/journal/12648)
- [Ciencia ergo-sum](https://cienciaergosum.uaemex.mx)
- [Frontiers in Public Health](https://www.frontiersin.org/articles/10.3389/fpubh.2022.939758/full)

### Editorial and evaluation activities

- Reviewer for COMIA 2026.
- Reviewer for CRC Press (2025).
- External evaluator for the *Internal Research Grants Programme*, University of Malta (2025).
- Reviewer for CONACYT postdoctoral grants (2023).
