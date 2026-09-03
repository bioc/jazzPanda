<!-- badges: start -->
[![DOI](https://zenodo.org/badge/724929670.svg)](https://zenodo.org/doi/10.5281/zenodo.10360070)
[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://github.com/phipsonlab/jazzPanda/blob/main/LICENSE)
[![R-CMD-check](https://github.com/phipsonlab/jazzPanda/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/phipsonlab/jazzPanda/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/phipsonlab/jazzPanda">
    <img src="https://github.com/phipsonlab/jazzPanda/blob/main/inst/images/jazzPanda_logo.png" alt="Logo" width="200" height="200">
  </a>

<h3 align="center">jazzPanda: A hybrid approach to find spatially relevant marker genes 
 
  in image-based spatial transcriptomics data </h3>

  <p align="center">
    <br />
    <a href="https://phipsonlab.github.io/jazzPanda/articles/jazzPanda.html"><strong>Explore the vignette »</strong></a>
    <br />
    <br />
  </p>
</div>

## Introduction

The jazzPanda package contains functions to find marker genes
based on the spatial coordinates for imaging-based spatial transcriptomics 
technologies including 10x Xenium, NanoString CosMx and Vizgen MERSCOPE. 


## Installation

To install jazzPanda from Bioconductor, use the following commands:

``` r
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")

BiocManager::install("jazzPanda")
```

To install jazzPanda from github, use the following commands:
``` r
library(devtools)
devtools::install_github("phipsonlab/jazzPanda")
```

In order to view the vignette for jazzPanda use the following command:

``` r
browseVignettes("jazzPanda")
```

## Example analyses

Worked analyses applying jazzPanda to a range of imaging-based spatial
transcriptomics datasets (10x Xenium, NanoString CosMx and Vizgen MERSCOPE)
are available as a `workflowr` website:

- Analysis website: <https://phipsonlab.github.io/jazzPanda_workflowr/>

## Citation
 
If you use jazzPanda in your research, please cite our preprint:
 
> Jin X, Putri GH, Cheng J, Asselin-Labat M-L, Smyth GK, Phipson B (2026).
> jazzPanda: spatially aware marker gene detection for imaging-based 
> spatial transcriptomics. *bioRxiv*.
> doi: [10.64898/2026.02.13.705867](https://doi.org/10.64898/2026.02.13.705867)