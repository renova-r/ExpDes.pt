# ExpDes.pt

Analysis of experimental designs (completely randomized, randomized block, Latin square, factorial, split-plot and others) with multiple comparison tests, documented in Portuguese.

Compatibility updates by Renova.

Version 1.2.2.9001 rewrites one braced accent in a reference in the `ccF` help page (`CALI\'{N}SKI`) so that `R CMD check` no longer reports "Lost braces". No R function was changed.

## Install

```r
install.packages("ExpDes.pt", repos = c(
  Renova = "https://renova-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))
```

Or install this exact release from its tag:

```r
install.packages("remotes")
remotes::install_github("renova-r/ExpDes.pt@renova-1.2.2.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

ExpDes.pt is by Eric Batista Ferreira (maintainer), Portya Piscitelli Cavalcanti and Denismar Alves Nogueira; the original CRAN package is at <https://CRAN.R-project.org/package=ExpDes.pt>. Some help pages note code adapted from agricolae (Felipe de Mendiburu) and from Laercio Junio da Silva's Scott-Knott code, both GPL. License: GPL (>= 2); see [COPYING](COPYING).
