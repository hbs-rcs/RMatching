# Causal Inference via Matching in R

Contact: [Research Computing Services](https://training.rcs.hbs.org/) ([research@hbs.edu](mailto:research@hbs.edu))  

## Overview

This workshop provides a step-by-step guide on how to preprocess data using matching methods for the purpose
of estimating a causal treatment effects in observational data. The demonstrated methods include nearest neighbor propensity score matching as well as Coarsened Exact Matching. The emphasis is made on analytic and graphical diagnosis of covariate balance. 

## Software

Before getting started, you should download and install R and RStudio.

* [R](http://cran.r-project.org)
* [Rtools](http://cran.r-project.org/bin/windows/Rtools/) (Windows Only)
* [RStudio](http://www.rstudio.com/ide/download/desktop)

This workshop assumes intermediate knowledge of R and does not cover the basics. If you are new to R, there are many great resources for learning:

* [Quick-R](http://statmethods.net/) - A great general purpose reference website covering basic and advanced R topics.
* [R in Action](http://www.manning.com/kabacoff/) - This book by Kabacoff is originated from the Quick-R website and is a fantastic book for learning R.
* [StackOverflow](http://stackoverflow.com/tags/R) - This website is a great place to go to ask questions and get help on R related topics.

## R Packages

There are a number of R packages available for conducting matching and balance checking. This workshop covers the following:

* [`MatchIt`](http://gking.harvard.edu/gking/matchit) (Ho, Imai, King, & Stuart, 2011) Nonparametric Preprocessing for Parametric Causal Inference
* [`cem`](https://gking.harvard.edu/files/gking/files/jss-paper.pdf) (Iacus, King, & Porro, 2018) Coarsened Exact Matching
* [`cobalt`](https://cran.r-project.org/web/packages/cobalt/vignettes/cobalt_A0_basic_use.html) Covariate Balance Tables and Plots.
