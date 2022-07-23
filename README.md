
<!-- README.md is generated from README.Rmd. Please edit that file -->

# regexcite

<!-- badges: start -->
<!-- badges: end -->

The goal of regexcite is to convenience functions to make some common
tasks with string manipulation and regular expressions a bit easier.

## Installation

You can install the development version of regexcite from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("Shitao5/regexcite")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(regexcite)
## basic example code
str_split_one("a,b,c", ",")
#> [1] "a" "b" "c"
str_split_one("a,b,c", ",", n = 2)
#> [1] "a"   "b,c"
```
