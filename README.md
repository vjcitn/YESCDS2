# YESCDS2
Updating YESCDS with webr

To make this work, one needs to `quarto add coatless/quarto-webr` in the folder where
qmd will be compiled.  The repos and packages are specified in the qmd header.

Then run quarto render on any qmd.  HTML will be produced.  An index.html is needed in /docs.

pkgdown does not seem to handle webr quarto at this time (23 mar 2024)
