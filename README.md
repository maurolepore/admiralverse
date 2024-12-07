
<!-- README.md is generated from README.Rmd. Please edit that file -->

# admiralverse

<!-- badges: start -->

<!-- badges: end -->

<div style="background-color: #ffcccc; padding: 10px; border: 1px solid 
#ff0000; border-radius: 5px;">

**WARNING:** This is a toy example. The real packages live at
[pharmaverse.org](https://pharmaverse.org/).

</div>

------------------------------------------------------------------------

The goal of admiralverse is to show by example how to create a simple
yet useful meta-package – to centralize the installation, use and
documentation of a collection of admiral packages.

## Installation

You can install the development version of admiralverse from
[GitHub](https://github.com/) with:

``` r
# install.packages("pak")
pak::pak("maurolepore/admiralverse")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(admiralverse)
#> Loading required package: admiral
#> Loading required package: admiraldev
#> Loading required package: admiralonco
#> 
#> Attaching package: 'admiralonco'
#> The following objects are masked from 'package:admiral':
#> 
#>     death_event, lastalive_censor
#> Loading required package: admiralophtha
#> Loading required package: admiralpeds
#> Loading required package: admiralvaccine
```
