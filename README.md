
<!-- README.md is generated from README.Rmd. Please edit that file -->

# compstatr <img src="man/figures/logo.png" align="right" />

[![lifecycle](https://img.shields.io/badge/lifecycle-maturing-blue.svg)](https://www.tidyverse.org/lifecycle/#maturing)
[![Travis-CI Build
Status](https://travis-ci.org/slu-openGIS/compstatr.svg?branch=master)](https://travis-ci.org/slu-openGIS/compstatr)
[![AppVeyor Build
Status](https://ci.appveyor.com/api/projects/status/github/slu-openGIS/compstatr?branch=master&svg=true)](https://ci.appveyor.com/project/chris-prener/compstatr)
[![Coverage
status](https://codecov.io/gh/slu-openGIS/compstatr/branch/master/graph/badge.svg)](https://codecov.io/github/slu-openGIS/compstatr?branch=master)
[![CRAN\_Status\_Badge](http://www.r-pkg.org/badges/version/compstatr)](https://cran.r-project.org/package=compstatr)

The goal of `compstatr` is to provide a suite of tools for working with
crime data made public by the City of St. Louis’s [Metropolitan Police
Department](http://www.slmpd.org).

## Motivation

Among cities in the United States, St. Louis has the distinction of
having the highest or one of the highest violent crime and homicide
rates since 2010. It therefore presents an important site for social
scientists, public health researchers, and health care providers as well
as policy makers to understand the effects of violent crime on urban
communities.

The City’s crime data, however, are diffuclt to work with and present a
challenge for researchers. These data are inconsistently organized, with
all data before 2013 and some months of 2013 itself having eighteen
variables. Beginning during 2013, most (but not all) months have twenty
variables, many of which are named differently from their pre-2014
counterparts. These inconsistencies, and the fact that working with
their data requires mangaing over 120 spreadsheets that each download
with with a `.html` file extension, are the motivating force behind
`compstatr`.

We therefore provide a set of tools for accessing, preparing, editing,
and mapping St. Louis [Metropolitan Police
Department](http://www.slmpd.org) (SLMPD) crime data, which are
available [on their website](http://www.slmpd.org/Crimereports.shtml) as
`.csv` files.

## Installation

You can install compstatr from Github with `remotes`:

``` r
# install.packages("remotes")
remotes::install_github("slu-openGIS/compstatr")
```

## Acknowledgements

We wish to thank Taylor Braswell for his significant efforts compiling
Stata code early in this project. Taylor’s code was used as a reference
when developing this package, and many of the functions reflect issues
that he worked to identify.

## Contributor Code of Conduct

Please note that this project is released with a [Contributor Code of
Conduct](.github/CODE_OF_CONDUCT.md). By participating in this project
you agree to abide by its terms.
