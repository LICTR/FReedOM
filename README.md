# FReedOM simulation study

This repo contains all code and simulation results supporting the sample size calculations for the FReedOM trial. The rendered simulation study is available at [lictr.github.io/FReedOM/](https://lictr.github.io/FReedOM/). The computationally intensive simulations are not rerun when the site is rendered. The code used to generate them is included in index.qmd, with the saved .rds files used to reproduce the reported results and figures.

Files
index.qmd — Quarto document containing the simulation methods, R code, analysis and results.
raw_sims_214.rds — pre-generated simulation results used for the main power calculations.
raw_sims_sens.rds — pre-generated results used for the sensitivity analysis.
FReedOM_refs.bib - BibTeX file of cited references.
_quarto.yml — configuration for the Quarto website.
.github/workflows/publish.yml — GitHub Actions workflow used to render and publish the website automatically.

