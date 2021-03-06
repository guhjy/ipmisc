
<!-- README.md is generated from README.Rmd. Please edit that file -->

# ipmisc

[![packageversion](https://img.shields.io/badge/Package%20version-0.1.1-orange.svg?style=flat-square)](commits/master)
[![Travis Build
Status](https://travis-ci.org/IndrajeetPatil/ipmisc.svg?branch=master)](https://travis-ci.org/IndrajeetPatil/ipmisc)
[![AppVeyor Build
Status](https://ci.appveyor.com/api/projects/status/github/IndrajeetPatil/ipmisc?branch=master&svg=true)](https://ci.appveyor.com/project/IndrajeetPatil/ipmisc)
[![Coverage
Status](https://img.shields.io/codecov/c/github/IndrajeetPatil/ipmisc/master.svg)](https://codecov.io/github/IndrajeetPatil/ipmisc?branch=master)
[![Licence](https://img.shields.io/badge/licence-GPL--3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0.en.html)
[![Last-changedate](https://img.shields.io/badge/last%20change-2018--03--21-yellowgreen.svg)](/commits/master)
[![lifecycle](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
[![minimal R
version](https://img.shields.io/badge/R%3E%3D-3.2.0-6666ff.svg)](https://cran.r-project.org/)

## Overview

The goal of ipmisc is to gather miscellaneous helper functions that have
been helpful to me in data cleaning and analysis.

## Installation

You can install `ipmisc` from GitHub with:

``` r
# install.packages("devtools")
devtools::install_github("IndrajeetPatil/ipmisc")
```

## Documentation

For documentation, please check out the vignettes folder of the package.

Note that the current package build is faling because the function
`ipmisc::summary_skim` and `ipmisc::partialeta_sq_ci`depend on the
development version of `skimr` and `sjstats`, which can be downloaded
here:

``` r
# library(devtools)
# skimr
devtools::install_github("ropenscilabs/skimr")

# sjstats
devtools::install_github("strengejacke/sjstats")
```
