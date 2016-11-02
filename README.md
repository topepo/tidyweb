
<!-- README.md is generated from README.Rmd. Please edit that file -->
<style>
small.tidyverse {display: none;}
.navbar .navbar-brand {
  font-size: 50px;
  padding: 10px 0 0 0;
  background-image: none;
}
.navbar {
  height: 80px;
}
body {
  position: relative;
  padding-top: 100px;
}
</style>
The tidyverse
=============

Components
----------

<a href='http://forcats.tidyverse.org'><img src='http://forcats.tidyverse.org/logo.png' width='120' height='139' /></a><a href='http://ggplot2.tidyverse.org'><img src='http://ggplot2.tidyverse.org/logo.png' width='120' height='139' /></a><a href='http://haven.tidyverse.org'><img src='http://haven.tidyverse.org/logo.png' width='120' height='139' /></a><a href='http://readr.tidyverse.org'><img src='http://readr.tidyverse.org/logo.png' width='120' height='139' /></a><a href='http://stringr.tidyverse.org'><img src='http://stringr.tidyverse.org/logo.png' width='120' height='139' /></a><a href='http://tidyr.tidyverse.org'><img src='http://tidyr.tidyverse.org/logo.png' width='120' height='139' /></a>

The tidyverse is a collection of R packages that share common philosophies and are designed to work together. This site is a work-in-progress guide to the tidyverse and its packages.

If you are new to the tidyverse, the best place to learn the complete philsophy and how everything fits together is the [R for data science](http://r4ds.had.co.nz/) book. This book is available for free online, and can you order a physical copy from [Amazon](http://amzn.to/2aHLAQ1) (currently taking pre-orders, the book should be out by the end of the year).

Installation
------------

Install the complete tidyverse with a single line of code:

``` r
install.packages("tidyverse")
```

Load the **core** tidyverse packages: ggplot2, tibble, tidyr, [readr](http://readr.tidyverse.org), purrr, and dplyr. These are the packages you are likely to use in almost every analyis.

``` r
library(tidyverse)
#> Loading tidyverse: ggplot2
#> Loading tidyverse: tibble
#> Loading tidyverse: tidyr
#> Loading tidyverse: readr
#> Loading tidyverse: purrr
#> Loading tidyverse: dplyr
#> Find out what's changed in ggplot2 at
#> http://github.com/hadley/ggplot2/releases.
#> Conflicts with tidy packages ----------------------------------------------
#> filter():  dplyr, stats
#> is_null(): purrr, testthat
#> lag():     dplyr, stats
#> matches(): dplyr, testthat
```
