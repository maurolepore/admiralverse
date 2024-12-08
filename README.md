
<!-- README.md is generated from README.Rmd. Please edit that file -->

# admiralverse

<!-- badges: start -->

<!-- badges: end -->

<div style="background-color: #ffcccc; padding: 10px; border: 1px solid 
#ff0000; border-radius: 5px;">

**WARNING:** This admiralverse is a toy example. For real code see the
[pharmaverse.org](https://pharmaverse.org/).

</div>

------------------------------------------------------------------------

The goal of admiralverse is to model the main use case of the
[dverse](https://maurolepore.github.io/dverse/) package.

Explore the [source code](https://github.com/maurolepore/admiralverse)
of this package to learn how to create a minimal meta-package for any
collection of R packages (i.e. a universe), and a website that allows
users to search vignettes, datasets, and functions across the entire
universe.

## Installation

You can install the development version of admiralverse from
[GitHub](https://github.com/) with:

``` r
# install.packages("pak")
pak::pak("maurolepore/admiralverse")
```

## Example

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
