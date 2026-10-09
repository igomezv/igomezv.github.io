---
layout: page
title: Research

---

My current research focuses on modelling stellar activity in radial-velocity and photometric data to support exoplanet detection. I use machine learning and Bayesian inference to develop and assess these methods, building on earlier work in cosmology. I welcome collaborations in these areas.


- [Publications](#publications) · [All publications](https://igomezv.github.io/full_papers/)
- [Code](#selected-code) · [All code](https://igomezv.github.io/code/)
- [Presentations](#presentations) · [All presentations](https://igomezv.github.io/full_presentations/)
- [Scientific service](#scientific-service)

-----

## Publications

For a complete publication list, see [<u>All publications</u>](https://igomezv.github.io/full_papers/).

| [<u>ADS</u>](https://ui.adsabs.harvard.edu/public-libraries/T0oALfuqQqSqUArTO-Gl1Q) | [<u>Google Scholar</u>](https://scholar.google.com.mx/citations?user=c9OLfMcAAAAJ&hl=es) | [<u>ORCID</u>](https://orcid.org/0000-0002-6473-018X) | [<u>ResearchGate</u>](https://www.researchgate.net/profile/Isidro-Gomez-Vargas) | [<u>WoS</u>](https://www.webofscience.com/wos/author/record/GYD-5531-2022) | [<u>arXiv</u>](https://arxiv.org/search/?searchtype=author&query=G%C3%B3mez-Vargas%2C+I) |
<br>

### Selected Lead-Author Publications

For the complete list, see [<u>Led and co-led</u>](https://igomezv.github.io/full_papers/#led-and-co-led).

- [**Gómez-Vargas, I.**, Dumusque, X., Zhao, Y., Al Moulla, K. & Cretignier, M. (2026). Modeling Doppler Shifts in radial-velocity data with deep learning toward Earth-mass exoplanet detection. Astronomy & Astrophysics. 712, A31.](https://doi.org/10.1051/0004-6361/202659375) <br>
<span class="publication-contributions" markdown="span">**Role:** Lead and corresponding author. Developed the deep-learning framework and the associated [doppleriann Python library](https://github.com/igomezv/doppleriann), and conducted the analysis. <br>
**Contribution to the field:** Developed and validated a physically motivated deep-learning framework for recovering and characterising weak planetary Doppler signals from real solar spectra. In cross-validation tests on HARPS-N observations with injected signals, the best-performing model recovered amplitudes, phases, and periods for signals with amplitudes down to 25 cm/s and periods of 10–550 days. The study compared temperature- and flux-based spectral representations and assessed predictive uncertainty and generalisation to unseen spectra, supporting progress towards Earth-mass planet detection.</span>

- [**Gómez-Vargas, I.**, & Vázquez, J. A. (2024). Deep learning and genetic algorithms for cosmological Bayesian inference speed-up. Physical Review D. 110(8), 083518.](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.110.083518) <br>
<span class="publication-contributions" markdown="span">**Role:** Lead and corresponding author. Developed and implemented the inference framework, conducted the data analysis, and created the associated [neuralike Python library](https://github.com/igomezv/neuralike). <br>
**Contribution to the field:** Introduced an approach to accelerating cosmological Bayesian inference by training neural networks to approximate likelihood functions on-the-fly during nested sampling, using the current live points without pretraining. Genetic algorithms guide the initial network architecture, and the neural network replaces the original likelihood function once sufficient accuracy is achieved. Tests across dark-energy models and observational datasets demonstrate the method’s applicability to different inference problems.</span>

- [**Gómez-Vargas, I.**, Andrade, J. B., & Vázquez, J. A. (2023). Neural networks optimized by genetic algorithms in cosmology. Physical Review D. 107(4), 043509.](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.107.043509) <br>
<span class="publication-contributions" markdown="span">**Role:** Lead author. Developed and implemented the methodology, conducted the analysis, and created the associated [nnogada framework](https://github.com/igomezv/nnogada). <br>
**Contribution to the field:** Introduced genetic-algorithm optimisation of neural-network architectures for cosmological regression problems, where even small prediction errors can matter for physical interpretation. Across distance-modulus reconstruction, quintessence equation-of-state inference, and photometric-redshift prediction, the optimised networks achieved better predictive performance than those selected through exhaustive grid searches. The study established systematic hyperparameter selection as a practical means of improving the precision of neural-network modelling in cosmology.</span>

- [**Gómez-Vargas, I.**, Vázquez, J. A., Esquivel, R. M., & García-Salcedo, R. (2023). Neural network reconstructions for the Hubble parameter, growth rate and distance modulus. European Physical Journal C. 83(4), 304.](https://doi.org/10.1140/epjc/s10052-023-11435-9) <br>
<span class="publication-contributions" markdown="span">**Role:** Lead author. Developed and implemented the reconstruction methodology and created the associated [software](https://github.com/igomezv/neuralCosmoReconstruction). <br>
**Contribution to the field:** Introduced a neural-network framework for reconstructing cosmological functions from small observational datasets with minimal theoretical and statistical assumptions. Applications to the Hubble parameter, growth rate, and supernova distance modulus demonstrated its use for data-driven reconstruction and consistency checks against the original observations. The study also explored variational autoencoders as a first step towards generating synthetic covariance matrices that represent observational correlations.</span>


### Selected Collaborative Publications

For the complete list, see [<u>Collaborative</u>](https://igomezv.github.io/full_papers/#collaborative).

- [Di Valentino, E., et al. (including **Gómez-Vargas, I.**) (2025). The CosmoVerse White Paper: Addressing observational tensions in cosmology with systematics and fundamental physics. <i>Physics of the Dark Universe</i>, 101965.](https://www.sciencedirect.com/science/article/pii/S221268642500158X) <br>
<span class="publication-contributions" markdown="span">**Role:** Contributed to Sections 3.3 and 3.4 on reconstruction techniques and bioinspired algorithms, including the neural-network reconstruction results shown in Fig. 64. <br>
**Contribution to the field:** The white paper synthesises observational tensions in cosmology, possible systematic effects, proposed new physics, and emerging analysis methods, providing a research roadmap for the coming decade.</span>

- [Zhao, Y., Dumusque, X., Cretignier, M., Cameron, A. C., Latham, D. W., López-Morales, M., Mayor, M., Sozzetti, A., Cosentino, R., **Gómez-Vargas, I.**, Pepe, F., & Udry, S. (2024). Improving Earth-like planet detection in radial velocity using deep learning. Astronomy & Astrophysics. 687, A281.](https://doi.org/10.1051/0004-6361/202450022) <br>
<span class="publication-contributions" markdown="span">**Role:** Reviewed the manuscript and contributed to methodological discussions of neural-network approaches for radial-velocity-based exoplanet detection. <br>
**Contribution to the field:** Demonstrated the use of convolutional neural networks to model stellar activity from spectral-line profile variations, improving sensitivity to weak planetary signals. Applications to Alpha Centauri B, Tau Ceti, and HARPS-N solar observations illustrated the potential of deep learning for activity mitigation in radial-velocity searches.</span>


-----
## Selected Code

---

Additional projects and software repositories are available on my [<u>GitHub profile</u>](https://github.com/igomezv) or in [<u>All code projects</u>](https://igomezv.github.io/code).

### doppleriann

**Doppler-shift Inference with Artificial Neural Networks (DopplerIANN)**

`doppleriann` is a Python package for modelling Doppler shifts in high-resolution stellar spectra using physically motivated spectral-shell representations and deep learning. It implements the framework presented in our paper [Gómez-Vargas et al. (2026). A&A, 712, A31.](https://doi.org/10.1051/0004-6361/202659375)

- GitHub repository: [igomezv/doppleriann](https://github.com/igomezv/doppleriann)
- Documentation: [doppleriann/Docs](https://igomezv.github.io/doppleriann/)

![Figura](https://igomezv.github.io/assets/img/doppleriann_workflow.png){: .mx-auto.d-block :}
![Figura](https://igomezv.github.io/assets/img/doppleriann_periodogram.png){: .mx-auto.d-block :}


---

### nnogada

**Neural networks optimised with genetic algorithms for data-driven inference and reconstruction.**

`nnogada` (**Neural Networks Optimized by Genetic Algorithms in Data Analysis**) is a framework combining neural networks and genetic algorithms for flexible modelling, reconstruction, and parameter inference in astrophysical and cosmological applications.

**Links**

- GitHub repository: [igomezv/nnogada](https://github.com/igomezv/nnogada)  
- Documentation: [docs/nnogada](https://igomezv.github.io/nnogada)  

![Figura](https://raw.githubusercontent.com/igomezv/igomezv.github.io/main/assets/img/nnogada.png){: .mx-auto.d-block :}

**Projects using `nnogada`**

- [igomezv/Reconstructing-RC-with-ANN](https://github.com/igomezv/Reconstructing-RC-with-ANN)  
- [igomezv/LSST_DE_neural_reconstruction](https://github.com/igomezv/LSST_DE_neural_reconstruction)  
- [igomezv/neuralike](https://github.com/igomezv/neuralike)  

---

### neuralike

**Deep-learning surrogate models for faster cosmological Bayesian inference.**

`neuralike` combines deep-learning surrogate models with genetic-algorithm optimisation to accelerate Bayesian inference in cosmology by approximating computationally expensive likelihood evaluations.

**Links**

- GitHub repository: [igomezv/neuralike](https://github.com/igomezv/neuralike)  
- Integration with `SimpleMC` and nested sampling using `dynesty`: [igomezv/simplemc_tests](https://github.com/igomezv/simplemc_tests/tree/neuralike)  

![Figura](https://raw.githubusercontent.com/igomezv/igomezv.github.io/main/assets/img/neuralike.png){: .mx-auto.d-block :}


---

### SimpleMC

**Cosmological parameter inference toolkit for Bayesian analysis and statistical sampling.**

`SimpleMC` is a cosmological parameter estimation framework originally developed by Dr. A. Slosar and Dr. J. A. Vázquez. Between **2019 and 2023**, I contributed to the development and maintenance of the codebase, including nested sampling implementations, convergence criteria for Metropolis–Hastings algorithms, post-processing utilities, and additional analysis modules.

**Links**

- GitHub repository: [ja-vazquez/SimpleMC](https://github.com/ja-vazquez/SimpleMC)  
- Documentation: [igomezv/SimpleMC/Docs](https://igomezv.github.io/SimpleMC)  
- Workshop/tutorial: [igomezv/simplemc_workshop](https://github.com/igomezv/simplemc_workshop)  

![Figura](https://igomezv.github.io/assets/img/triangleSimplemc.png){: .mx-auto.d-block :}


-----
## Presentations
-----

**Selected** invited talks, conference presentations, and seminars.
For the complete list, including posters, see [<u>All presentations</u>](https://igomezv.github.io/full_presentations/).

- **2026**
	- [Talk] [*Beyond Harvey-like models: studying the shared residual structure of the stellar background*.](https://asteroseismology.iaa.es/inma-meeting) INMA kick-off meeting, Instituto de Astrofísica de Andalucía (IAA-CSIC). Meeting chair. [Hybrid].
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

### Review and evaluation activities

- **Conference reviewer**: [MICAI 2026](https://micai.org/2026/), [COMIA 2026](http://smia.itmorelos.mx/reconocimientos_comia/revisores2026.php?idn=MTEw).
- **Book reviewer**: CRC Press (2025).
- **Grant evaluator**: [*Internal Research Grants Programme*, University of Malta (2025)](https://www.dropbox.com/scl/fi/efw1yucijonrxu12g69mp/Malta_Reviewer_Certification.pdf?rlkey=vtkbl05zebisyvw1z36u51c7u&st=hhzv4mt8&dl=0), and CONACYT postdoctoral grants (2023).
