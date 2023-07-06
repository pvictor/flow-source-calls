
<!-- README.md is generated from README.Rmd. Please edit that file -->

## Explore `source` & `sourceDirectory` with [flow](https://github.com/moodymudskipper/flow)

``` r
library(flow)
scripts <- list.files(".", pattern = "\\.R$", full.names = FALSE, recursive = TRUE)
flow_view_source_calls(scripts, basename = FALSE, extension = TRUE)
```

With CRAN version :
![](figures/flow-cran.png)

With GitHub version (`flow        * 0.2.0.9000 2023-07-06 [1] Github (moodymudskipper/flow@292c989)`) :

```r
Erreur dans (function (..., row.names = NULL, check.rows = FALSE, check.names = TRUE,  : 
  les arguments impliquent des nombres de lignes différents : 5, 0
```