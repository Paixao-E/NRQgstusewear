
<!-- README.md is generated from README.Rmd. Please edit that file -->

# NRQgstusewear

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Paixao-E/NRQgstusewear/master?urlpath=rstudio)

This repository contains the data and code for our paper:

> Eduardo Paixão; João Marreiros; Laure Dubreuil; Walter Gneisinger;
> Geoff Carver; Marion Prévost; Yossi Zaidner, (2021).
> *`The Middle Paleolithic Ground Stones Tools of Nesher Ramla Unit V (Southern Levant): a multi-scale use-wear approach for assessing the assemblage functional variability`*.
> Quaternary International <https://doi.org/xxx/xxx>

Our pre-print is online here:

> Eduardo Paixão; João Marreiros; Laure Dubreuil; Walter Gneisinger;
> Geoff Carver; Marion Prévost; Yossi Zaidner, (2021). *The Middle
> Paleolithic Ground Stones Tools of Nesher Ramla Unit V (Southern
> Levant): a multi-scale use-wear approach for assessing the assemblage
> functional variability*. Name of journal/book, Accessed 05 May 2021.
> Online at <https://doi.org/xxx/xxx>

### How to cite

Please cite this compendium as:

> Eduardo Paixão; João Marreiros; Laure Dubreuil; Walter Gneisinger;
> Geoff Carver; Marion Prévost; Yossi Zaidner, (2021). *Compendium of R
> code and data for The Middle Paleolithic Ground Stones Tools of Nesher
> Ramla Unit V (Southern Levant): a multi-scale use-wear approach for
> assessing the assemblage functional variability*. Accessed 05 May
> 2021. Online at <https://doi.org/xxx/xxx>

## Contents

The **analysis** directory contains:

-   [:file\_folder: scripts](/analysis/paper): R Markdown source
    document for manuscript. Includes code to reproduce the figures and
    tables generated by the analysis. It also has a rendered version,
    `paper.docx`, suitable for reading (the code is replaced by figures
    and tables in this file)
-   [:file\_folder: raw\_data](/analysis/raw_data): Raw data used in the
    analysis.
-   [:file\_folder: derived\_data](/analysis/derived_data): Derived data
    generated from the analysis.
-   [:file\_folder: summary\_stats](/analysis/summary_stats): summary of
    the statistical analysis.
-   [:file\_folder: plots](/analysis/plots): Plots and other
    illustrations

## How to run in your broswer or download and run locally

This research compendium has been developed using the statistical
programming language R. To work with the compendium, you will need
installed on your computer the [R
software](https://cloud.r-project.org/) itself and optionally [RStudio
Desktop](https://rstudio.com/products/rstudio/download/).

The simplest way to explore the text, code and data is to click on
[binder](https://mybinder.org/v2/gh/Paixao-E/NRQgstusewear/master?urlpath=rstudio)
to open an instance of RStudio in your browser, which will have the
compendium files ready to work with. Binder uses rocker-project.org
Docker images to ensure a consistent and reproducible computational
environment. These Docker images can also be used locally.

You can download the compendium as a zip from from this URL:
[master.zip](/archive/master.zip). After unzipping: - open the `.Rproj`
file in RStudio - run `devtools::install()` to ensure you have the
packages this analysis depends on (also listed in the
[DESCRIPTION](/DESCRIPTION) file). - finally, open
`analysis/paper/paper.Rmd` and knit to produce the `paper.docx`, or run
`rmarkdown::render("analysis/paper/paper.Rmd")` in the R console

### Licenses

**Text and figures :**
[CC-BY-4.0](http://creativecommons.org/licenses/by/4.0/)

**Code :** See the [DESCRIPTION](DESCRIPTION) file

**Data :** [CC-0](http://creativecommons.org/publicdomain/zero/1.0/)
attribution requested in reuse

### Contributions

We welcome contributions from everyone. Before you get started, please
see our [contributor guidelines](CONTRIBUTING.md). Please note that this
project is released with a [Contributor Code of Conduct](CONDUCT.md). By
participating in this project you agree to abide by its terms.
