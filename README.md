
<!-- README.md is generated from README.Rmd. Please edit that file -->

# pkgMetagenomica

<!-- badges: start -->

[![GitHub
issues](https://img.shields.io/github/issues/nselem/pkgMetagenomica)](https://github.com/nselem/pkgMetagenomica/issues)
[![GitHub
pulls](https://img.shields.io/github/issues-pr/nselem/pkgMetagenomica)](https://github.com/nselem/pkgMetagenomica/pulls)
[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![BioC
status](http://www.bioconductor.org/shields/build/release/bioc/pkgMetagenomica.svg)](https://bioconductor.org/checkResults/release/bioc-LATEST/pkgMetagenomica)
[![R-CMD-check-bioc](https://github.com/nselem/pkgMetagenomica/actions/workflows/R-CMD-check-bioc.yaml/badge.svg)](https://github.com/nselem/pkgMetagenomica/actions/workflows/R-CMD-check-bioc.yaml)
<!-- badges: end -->

The goal of `pkgMetagenomica` is to …

## Installation instructions

Get the latest stable `R` release from
[CRAN](http://cran.r-project.org/). Then install `pkgMetagenomica` from
[Bioconductor](http://bioconductor.org/) using the following code:

``` r
if (!requireNamespace("BiocManager", quietly = TRUE)) {
    install.packages("BiocManager")
}

BiocManager::install("pkgMetagenomica")
```

And the development version from
[GitHub](https://github.com/nselem/pkgMetagenomica) with:

``` r
BiocManager::install("nselem/pkgMetagenomica")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library("pkgMetagenomica")
## basic example code
```

What is special about using `README.Rmd` instead of just `README.md`?
You can include R chunks like so:

``` r
summary(cars)
#>      speed           dist       
#>  Min.   : 4.0   Min.   :  2.00  
#>  1st Qu.:12.0   1st Qu.: 26.00  
#>  Median :15.0   Median : 36.00  
#>  Mean   :15.4   Mean   : 42.98  
#>  3rd Qu.:19.0   3rd Qu.: 56.00  
#>  Max.   :25.0   Max.   :120.00
```

You’ll still need to render `README.Rmd` regularly, to keep `README.md`
up-to-date.

You can also embed plots, for example:

<img src="man/figures/README-pressure-1.png" width="100%" />

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub!

## Citation

Below is the citation output from using `citation('pkgMetagenomica')` in
R. Please run this yourself to check for any updates on how to cite
**pkgMetagenomica**.

``` r
print(citation('pkgMetagenomica'), bibtex = TRUE)
#> 
#> To cite package 'pkgMetagenomica' in publications use:
#> 
#>   nselem (2022). _pkgMetagenomica_.
#>   doi:10.18129/B9.bioc.pkgMetagenomica
#>   <https://doi.org/10.18129/B9.bioc.pkgMetagenomica>,
#>   https://github.com/nselem/pkgMetagenomica/pkgMetagenomica - R package
#>   version 0.0.0.9000,
#>   <http://www.bioconductor.org/packages/pkgMetagenomica>.
#> 
#> A BibTeX entry for LaTeX users is
#> 
#>   @Manual{,
#>     title = {pkgMetagenomica},
#>     author = {{nselem}},
#>     year = {2022},
#>     url = {http://www.bioconductor.org/packages/pkgMetagenomica},
#>     note = {https://github.com/nselem/pkgMetagenomica/pkgMetagenomica - R package version 0.0.0.9000},
#>     doi = {10.18129/B9.bioc.pkgMetagenomica},
#>   }
#> 
#>   nselem (2022). "pkgMetagenomica." _bioRxiv_. doi:10.1101/TODO
#>   <https://doi.org/10.1101/TODO>,
#>   <https://www.biorxiv.org/content/10.1101/TODO>.
#> 
#> A BibTeX entry for LaTeX users is
#> 
#>   @Article{,
#>     title = {pkgMetagenomica},
#>     author = {{nselem}},
#>     year = {2022},
#>     journal = {bioRxiv},
#>     doi = {10.1101/TODO},
#>     url = {https://www.biorxiv.org/content/10.1101/TODO},
#>   }
```

Please note that the `pkgMetagenomica` was only made possible thanks to
many other R and bioinformatics software authors, which are cited either
in the vignettes and/or the paper(s) describing this package.

## Code of Conduct

Please note that the `pkgMetagenomica` project is released with a
[Contributor Code of
Conduct](http://bioconductor.org/about/code-of-conduct/). By
contributing to this project, you agree to abide by its terms.

## Development tools

-   Continuous code testing is possible thanks to [GitHub
    actions](https://www.tidyverse.org/blog/2020/04/usethis-1-6-0/)
    through *[usethis](https://CRAN.R-project.org/package=usethis)*,
    *[remotes](https://CRAN.R-project.org/package=remotes)*, and
    *[rcmdcheck](https://CRAN.R-project.org/package=rcmdcheck)*
    customized to use [Bioconductor’s docker
    containers](https://www.bioconductor.org/help/docker/) and
    *[BiocCheck](https://bioconductor.org/packages/3.15/BiocCheck)*.
-   Code coverage assessment is possible thanks to
    [codecov](https://codecov.io/gh) and
    *[covr](https://CRAN.R-project.org/package=covr)*.
-   The [documentation website](http://nselem.github.io/pkgMetagenomica)
    is automatically updated thanks to
    *[pkgdown](https://CRAN.R-project.org/package=pkgdown)*.
-   The code is styled automatically thanks to
    *[styler](https://CRAN.R-project.org/package=styler)*.
-   The documentation is formatted thanks to
    *[devtools](https://CRAN.R-project.org/package=devtools)* and
    *[roxygen2](https://CRAN.R-project.org/package=roxygen2)*.

For more details, check the `dev` directory.

This package was developed using
*[biocthis](https://bioconductor.org/packages/3.15/biocthis)*.
