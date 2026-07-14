---
layout: page
title: Research

---

Research focused on the intersection of deep learning, Bayesian inference, and astrophysics, with applications to cosmology, exoplanets, and stellar activity.

- [Publications](#publications) · [All publications](https://igomezv.github.io/full_papers/)
- [Software](#research-software) · [All code contributions](https://github.com/igomezv)
- [Presentations](#presentations) · [All presentations](https://igomezv.github.io/full_presentations/)
- [Scientific service](#scientific-service)

-----

## Publications

For a complete publication list, see [All publications](https://igomezv.github.io/full_papers/) or the profiles below:

| [<u>ADS</u>](https://ui.adsabs.harvard.edu/public-libraries/T0oALfuqQqSqUArTO-Gl1Q) | [<u>Google Scholar</u>](https://scholar.google.com.mx/citations?user=c9OLfMcAAAAJ&hl=es) | [<u>ORCID</u>](https://orcid.org/0000-0002-6473-018X) | [<u>ResearchGate</u>](https://www.researchgate.net/profile/Isidro-Gomez-Vargas) | [<u>WoS</u>](https://www.webofscience.com/wos/author/record/GYD-5531-2022) | [<u>arXiv</u>](https://arxiv.org/search/?searchtype=author&query=G%C3%B3mez-Vargas%2C+I) |
<br>

### Selected Lead-Author and Co-Led Publications

For the complete list, see [Led and co-led](https://igomezv.github.io/full_papers/#led-and-co-led).

- [**Gómez-Vargas, I.**, Dumusque, X., Zhao, Y., Al Moulla, K. & Cretignier, M. (2026). Modeling Doppler Shifts in radial-velocity data with deep learning toward Earth-mass exoplanet detection. Accepted in Astronomy & Astrophysics. arXiv:2606.18464.](https://doi.org/10.1051/0004-6361/202659375) <br>
**Contribution:** Lead and corresponding author. Developed the associated [code library](https://github.com/igomezv/doppleriann).

- [Chacón-Lavanderos, J., **Gómez-Vargas, I.**, Menchaca-Mendez, R., & Vázquez, J. A. (2026). Variational autoencoder for generating realistic N-body simulations for dark matter halos. Physical Review D. 113(6), 063520.](https://journals.aps.org/prd/abstract/10.1103/b6lj-rlff) <br>
**Contribution:** Co-lead and corresponding author. Co-developed the methodological framework and manuscript preparation; developed the associated [code repository](https://github.com/igomezv/NcosmoVAE); supervised the first author (PhD student).

- [**Gómez-Vargas, I.**, & Vázquez, J. A. (2024). Deep learning and genetic algorithms for cosmological Bayesian inference speed-up. Physical Review D. 110(8), 083518.](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.110.083518) <br>
**Contribution:** Lead author. Developed the inference framework, methodology, implementation, and data analysis; developed the associated [code repository](https://github.com/igomezv/nnogada).

- [Mitra, A., **Gómez-Vargas, I.**, & Zarikas, V. (2024). Dark energy reconstruction analysis with artificial neural networks: Application on simulated Supernova Ia data from Rubin Observatory. <i>Physics of the Dark Universe</i>, 46, 101706.](https://www.sciencedirect.com/science/article/pii/S2212686424002887) <br>
**Contribution:** Co-lead author and corresponding author. Led the methodological development, implementation, and analysis; developed the associated [code repository](https://github.com/igomezv/LSST_DE_neural_reconstruction).

- [**Gómez-Vargas, I.**, Andrade, J. B., & Vázquez, J. A. (2023). Neural networks optimized by genetic algorithms in cosmology. Physical Review D. 107(4), 043509.](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.107.043509) <br>
**Contribution:** Lead author. Developed the methodology, implementation, and analysis; developed the associated [code repository](https://github.com/igomezv/nnogada).

- [**Gómez-Vargas, I.**, Vázquez, J. A., Esquivel, R. M., & García-Salcedo, R. (2023). Neural network reconstructions for the Hubble parameter, growth rate and distance modulus. European Physical Journal C. 83(4), 304.](https://doi.org/10.1140/epjc/s10052-023-11435-9) <br>
**Contribution:** Lead author. Developed the reconstruction methodology and implementation; developed the associated [code repository](https://github.com/igomezv/neuralCosmoReconstruction).


### Selected Collaborative Publications

For the complete list, see [Collaborative](https://igomezv.github.io/full_papers/#collaborative).

- [Di Valentino, E., et al. (including **Gómez-Vargas, I.**) (2025). The CosmoVerse White Paper: Addressing observational tensions in cosmology with systematics and fundamental physics. <i>Physics of the Dark Universe</i>, 101965.](https://www.sciencedirect.com/science/article/pii/S221268642500158X) <br>
**Contribution:** Contributed to Sections 3.3 and 3.4 on reconstruction techniques and bioinspired algorithms, including the neural-network reconstruction results shown in Fig. 64.

- [Zhao, Y., Dumusque, X., Cretignier, M., Cameron, A. C., Latham, D. W., López-Morales, M., Mayor, M., Sozzetti, A., Cosentino, R., **Gómez-Vargas, I.**, Pepe, F., & Udry, S. (2024). Improving Earth-like planet detection in radial velocity using deep learning. Astronomy & Astrophysics. 687, A281.](https://doi.org/10.1051/0004-6361/202450022) <br>
**Contribution:** Contributed to manuscript review and methodological discussion of neural-network approaches for radial-velocity-based exoplanet detection.


-----
## Research software

---

Additional projects and software repositories are available on my [GitHub profile](https://github.com/igomezv) or in [Code section](https://igomezv.github.io/code).

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


-----
## Presentations
-----

**Selected invited** talks, conference presentations, and seminars.
Complete list, including posters, [<u>here</u>](https://igomezv.github.io/full_presentations/).

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

- [Physical Review Letters](https://journals.aps.org/prl/)
- [IEEE Transactions on Pattern Analysis and Machine Intelligence](https://ieeexplore.ieee.org/xpl/aboutJournal.jsp?punumber=34)
- [Physical Review D](https://journals.aps.org/prd/)
- [Journal of Cosmology and Astroparticle Physics](https://iopscience.iop.org/journal/1475-7516)
- [Physics of the Dark Universe](https://www.sciencedirect.com/journal/physics-of-the-dark-universe)
- [European Physical Journal C](https://link.springer.com/journal/10052)
- [Astronomy and Computing](https://www.sciencedirect.com/journal/astronomy-and-computing)
- [Indian Journal of Physics](https://link.springer.com/journal/12648)
- [Ciencia ergo-sum](https://cienciaergosum.uaemex.mx)
- [Frontiers in Public Health](https://www.frontiersin.org/articles/10.3389/fpubh.2022.939758/full)

### Review and Evaluation Activities

- **Conference reviewer**: [MICAI 2026](https://micai.org/2026/), [COMIA 2026](http://smia.itmorelos.mx/reconocimientos_comia/revisores2026.php?idn=MTEw).
- **Book reviewer**: CRC Press (2025).
- **Grant evaluator:**: [*Internal Research Grants Programme*, University of Malta (2025)](https://www.dropbox.com/scl/fi/efw1yucijonrxu12g69mp/Malta_Reviewer_Certification.pdf?rlkey=vtkbl05zebisyvw1z36u51c7u&st=hhzv4mt8&dl=0), and CONACYT postdoctoral grants (2023).
