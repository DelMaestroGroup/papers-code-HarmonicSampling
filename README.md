[![Paper](https://img.shields.io/badge/paper-arXiv%3A2511.04597-B31B1B.svg)](https://arxiv.org/abs/2511.04597)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.XXXXXXX.svg)](https://zenodo.org/badge/latestdoi/XXXXYYYYY)

# Combining Harmonic Sampling with the Worm Algorithm to Improve the Efficiency of Path Integral Monte Carlo

Sourav Karmakar, Sutirtha Paul, Adrian Del Maestro, Barak Hirshberg

[arXiv:2511.04597](https://arxiv.org/abs/2511.04597)

### Abstract

We propose an improved Path Integral Monte Carlo (PIMC) algorithm called Harmonic PIMC (H-PIMC) and its generalization, Mixed PIMC (M-PIMC). PIMC is a powerful tool for studying quantum condensed phases. However, it often suffers from a low acceptance ratio for solids and dense confined liquids. We develop two sampling schemes especially suited for such problems by dividing the potential into its harmonic and anharmonic contributions. In H-PIMC, we generate the imaginary time paths for the harmonic part of the potential exactly and accept or reject it based on the anharmonic part. In M-PIMC, we restrict the harmonic sampling to the vicinity of local minimum and use standard PIMC otherwise, to optimize efficiency. We benchmark H-PIMC on systems with increasing anharmonicity, improving the acceptance ratio and lowering the auto-correlation time. For weakly to moderately anharmonic systems, at βℏω=16, H-PIMC improves the acceptance ratio by a factor of 6-16 and reduces the autocorrelation time by a factor of 7-30. We also find that the method requires a smaller number of imaginary time slices for convergence, which leads to another two- to four-fold acceleration. For strongly anharmonic systems, M-PIMC converges with a similar number of imaginary time slices as standard PIMC, but allows the optimization of the auto-correlation time. We extend M-PIMC to periodic systems and apply it to a sinusoidal potential. Finally, we combine H- and M-PIMC with the worm algorithm, allowing us to obtain similar efficiency gains for systems of indistinguishable particles. 

### Description
This repository includes links, code, scripts, and data to generate the figures in a paper.

### Requirements
The data in this project was generated via ...  Processed data is included in the [data](https://github.com/DelMaestroGroup/papers-code-template/tree/main/data) directory and the full raw simulation data set is available online at [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.XXXXXXX.svg)](https://doi.org/10.5281/zenodo.XXXXXXXX)

1. A minimal environment to execute these notebooks can be installed via `pip install -r requirements.txt`
2. [Dependency Name](https://dependencelink)
3. ...

### Support
This work was performed with support from the U.S. Department of Energy, Office of Science, Office of Basic Energy Sciences, under Award Number DE-SC0024333.

<img width="400px" src="https://science.osti.gov/assets/img/doe-logos/logo.png">


### Figures

#### Figure 01: Figure Name
<img src="https://github.com/DelMaestroGroup/papers-code-template/blob/main/figures/figure01.svg" width="400px">

This figure is relesed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) and can be freely copied, redistributed and remixed.

