---
layout: page
title: Research
---

My research focuses on developing tailored methodologies and computational frameworks that integrate machine learning and statistical inference to extract physical information from complex astronomical data, with particular attention to interpretability, uncertainty, and weak-signal recovery. Initially centred on reconstructing cosmological observables and Bayesian inference, my work has expanded to stellar spectroscopy, exoplanet detection, and stellar variability. I combine neural-network, evolutionary, and probabilistic approaches with systematic hyperparameter optimisation and physically informed validation to improve the reliability of astrophysical inference, particularly when small modelling biases can significantly affect the physical interpretation of results.

**Further information:** [Publications](/full_papers/) · [Open-source code](/code/) · [Presentations](/full_presentations/) · [CV](/cv/)

## Stellar Variability and Exoplanet Detection

At the University of Geneva, I developed a deep-learning framework to infer Doppler shifts from high-resolution stellar spectra. The method combines physically motivated spectral representations with tailored training and planetary-signal injection–recovery tests to assess detectability in real observations. This work produced [*doppleriann*](/code/#doppleriann) and a [lead-author study in *Astronomy & Astrophysics* (2026)](https://doi.org/10.1051/0004-6361/202659375), alongside [collaborative research on stellar-activity mitigation (Zhao et al., 2024)](https://doi.org/10.1051/0004-6361/202450022).

![Periodograms comparing conventional radial velocities with deep-learning Doppler-shift estimates for an injected planetary signal](/assets/img/doppleriann_periodogram.png){: .mx-auto.d-block :}

*Injection–recovery test with HARPS-N solar spectra: deep-learning Doppler-shift estimates reveal an injected 100-day signal less apparent in conventional radial velocities ([Gómez-Vargas et al., 2026](https://doi.org/10.1051/0004-6361/202659375)).*

As an MSCA-COFUND ALLIES fellow at IAA-CSIC, jointly affiliated with ICE-CSIC, I investigate stellar variability through interpretable models of power spectra using symbolic regression and probabilistic generative models of photometric light curves. These complementary approaches seek shared variability patterns while accounting for differences between stars and observing conditions, with applications to Kepler, TESS, and PLATO. I [presented preliminary results at TASC10/KASC17 (2026)](https://doi.org/10.5281/zenodo.21281645); the manuscripts are in preparation.

![Observed stellar power spectrum compared with a fitted baseline and symbolic-regression, neural-network, and Gaussian-process residual reconstructions](/assets/img/stellar-psd-sr-comparison.png){: .mx-auto.d-block :}

*Stellar power-spectrum reconstruction using symbolic regression (SR), compared with neural-network (NN) and Gaussian-process (GP) residual models. The lower panel shows residuals in log power ([TASC10/KASC17 poster, 2026](https://doi.org/10.5281/zenodo.21281645)).*

My longer-term goal is to connect photometric variability with spectroscopic activity indicators to improve stellar characterisation and exoplanet searches. I also contribute generative-modelling expertise to the [SpeckleNet collaboration on high-contrast exoplanet imaging](https://meetingorganizer.copernicus.org/EPSC-DPS2025/EPSC-DPS2025-2087.html), extending this methodological work across complementary observing techniques.

## Astrophysical Statistical Inference

My research in astrophysical statistical inference originated in cosmology during my PhD at IPN and postdoctoral research at UNAM, addressing challenges involving limited datasets, uncertainty quantification, model selection, and computationally expensive Bayesian inference.

I developed a [neural-network reconstruction methodology](/code/#ann-reconstructions) applied to the Hubble parameter, growth rate, and supernova distance modulus, incorporating Monte Carlo dropout to estimate uncertainties and examining statistical consistency with the observations ([Gómez-Vargas et al., 2023, *EPJC*](https://doi.org/10.1140/epjc/s10052-023-11435-9)). I subsequently developed [*nnogada*](/code/#nnogada), a framework that uses genetic algorithms to optimise neural-network architectures and evaluates their performance across distinct cosmological tasks ([Gómez-Vargas et al., 2023, *PRD*](https://doi.org/10.1103/PhysRevD.107.043509)). These two strategies served as the methodological foundation for co-led studies on dark-energy reconstruction with [simulated Rubin Observatory supernova data (Mitra et al., 2024)](https://www.sciencedirect.com/science/article/pii/S2212686424002887) and [galaxy rotation curves (Garcia-Arroyo et al., 2026)](https://www.sciencedirect.com/science/article/pii/S2212686426000294).

![Neural networks optimised with genetic algorithms for cosmological modelling](/assets/img/nnogada.png){: .mx-auto.d-block :}

*Genetic-algorithm optimisation of neural-network architectures for cosmological reconstruction and inference ([Gómez-Vargas et al., 2023](https://doi.org/10.1103/PhysRevD.107.043509)).*

<div style="display:flex; justify-content:center; gap:15px; flex-wrap:wrap;">
  <img src="/assets/img/rec1.png" alt="Neural-network reconstruction of cosmological distance observations with uncertainty estimates" style="width:48%; min-width:280px; height:auto; object-fit:contain;" />
  <img src="/assets/img/rec2.png" alt="Supernova distance-modulus reconstruction with observational data and an uncertainty band" style="width:48%; min-width:280px; height:auto; object-fit:contain;" />
</div>

*Data-driven reconstructions of cosmological distance measurements and their uncertainties ([Gómez-Vargas et al., 2023](https://doi.org/10.1140/epjc/s10052-023-11435-9); [Mitra et al., 2024](https://www.sciencedirect.com/science/article/pii/S2212686424002887)).*

I contributed to the development and maintenance of [*SimpleMC*](/code/#simplemc), particularly its sampling, optimisation, and convergence tools, and explored [genetic algorithms for cosmological parameter estimation (Medel Esquivel et al., 2023)](https://www.mdpi.com/2218-1997/10/1/11). Building on this experience, I implemented [*neuralike*](/code/#neuralike), an inference framework for accelerating Bayesian inference by dynamically training neural networks to approximate computationally expensive likelihood functions during nested sampling. *neuralike* trains neural networks directly on live points generated during nested sampling, without requiring a separate training phase, and employs genetic algorithms to optimise network architectures and explore improved initialisation of live points. ([Gómez-Vargas & Vázquez, 2024, *PRD*](https://doi.org/10.1103/PhysRevD.110.083518)).

My collaborations also include machine-learning studies of [dark-matter halo structure (Chacón et al., 2023)](https://doi.org/10.1103/PhysRevD.107.123515) and [generative modelling of N-body simulations (Chacón-Lavanderos et al., 2026)](https://doi.org/10.1103/b6lj-rlff), as well as Bayesian analyses of cosmological models ([Vázquez et al., 2024](https://doi.org/10.1103/PhysRevD.109.023511); [Garcia-Salcedo et al., 2024](https://www.mdpi.com/2218-1997/10/9/353); [Tamayo et al., 2025](https://doi.org/10.1016/j.dark.2025.101901); [Chaudhary et al., 2026](https://doi.org/10.1140/epjc/s10052-026-15806-w)). I contributed to discussions of nonparametric reconstruction and metaheuristic methods in the [CosmoVerse White Paper (2025)](https://www.sciencedirect.com/science/article/pii/S221268642500158X). 