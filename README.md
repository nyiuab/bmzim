# bmzim: Bayesian models and zero-inflated models, with applications to microbiome data analysis

# Overview

This package provides functions for setting up and fitting various Bayesian models and zero-inflated models (negative binomial, Gaussian, Studen-t, and beta models), for numerically and graphically summarizing the fitted models, and for evaluating the predictive performance.These Bayesian models are fitted by using fast quasi-Newton algorithm for estimating posterior modes rather than MCMC. The methods can jointly analyze numerous and correlated predictors.

Author: Nengjun Yi nyi@uab.edu; Maintainer: Nengjun Yi nyi@uab.edu

# Installation

Two ways to install the package in R:

1. With Vignettes (must install packages: devtools, knitr, R.rsp)
```{r}
devtools::install_github("nyiuab/bmzim", build_opts = c("--no-resave-data", "--no-manual"), force = T)
```
2. Without Vignettes (must install package: devtools) 
```{r}
devtools::install_github("nyiuab/bmzim", force = T)
