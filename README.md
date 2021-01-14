-   [Introduction](#introduction)
-   [Installation](#installation)
-   [How to use the *mFD* package?](#how-to-use-the-mfd-package)
-   [Citation](#citation)
-   [Contributions](#contributions)

<!-- badges: start -->

[![CRAN
status](https://www.r-pkg.org/badges/version/mFD)](https://CRAN.R-project.org/package=mFD)
<!-- badges: end -->

<img src = "man/figures/mFDsticker.png" width = 120 alt = "mFD sticker"/>

Introduction
============

The *mFD* package provides a **“user friendly” interface** to compute a
**global assessment of functional diversity** by gathering computation
of alpha, beta functional indices. As no package before, it guides the
user through functional analysis with one function per action to
complete, several arguments that can be changed and allows personalized
graphical outputs. Various tutorials are available on the mFD website to
guide the user through the functional workflow.

Installation
============

The *mFD* package can be installed through CRAN as follow:

``` r
install.packages("mFD")
library(mFD)
```

or for the latest development version, the *mFD* Github repository can
be used:

``` r
library(devtools)
devtools::install_github("CmlMagneville/mFD", force = TRUE)
library(mFD)
```

How to use the *mFD* package?
=============================

To compute functional diversity indices, the user needs: \* a dataframe
summarizing species traits (species in rows, traits in columns). The mFD
package works with all kind of traits: quantitative, ordinal, nominal,
circular and fuzzy-coded. \* a dataframe summarizing species gathering
into assemblages (assemblages in rows, species in columns). All
assemblages must at least contain one species. \* a dataframe
summarizing traits category (first column with traits name, second
column with traits type, third column with fuzzy name of fuzzy traits -
if no fuzzy traits: NA).

For a complete understanding of the functional workflow and the packages
possibilities, please refer to the \[General mFD workflow vignette\]
<a href="https://github.com/CmlMagneville/mFD/docs/articles/mFD_general_workflow.html" class="uri">https://github.com/CmlMagneville/mFD/docs/articles/mFD_general_workflow.html</a>.

Citation
========

To cite package `mFD` in publications use:

ADD CITATION HERE

Contributions
=============

SV, NL, EM, FL and CM wrote the functions. SV, NL and CM wrote function
documentations. SV and CM wrote tutorials.
