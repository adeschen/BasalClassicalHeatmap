<!-- badges: start -->
[![R-CMD-check-bioc](https://github.com/adeschen/BasalClassicalHeatmap/actions/workflows/check-bioc.yaml/badge.svg)](https://github.com/adeschen/BasalClassicalHeatmap/actions/workflows/check-bioc.yaml)
[![codecov](https://codecov.io/gh/adeschen/BasalClassicalHeatmap/branch/main/graph/badge.svg?token=XVKU8S1E2R)](https://codecov.io/gh/adeschen/BasalClassicalHeatmap)
[![License: Artistic-2.0](https://img.shields.io/badge/License-Artistic%202.0-0298c3.svg)](https://opensource.org/licenses/Artistic-2.0)
<!-- badges: end -->

# BasalClassicalHeatmap

The __BasalClassicalHeatmap__ package enables Basal-like/Classical 
classification of pancreatic tumor 
samples by generating heatmaps using transcriptomic data. 

Three different lists of Basal-like/Classical genes are 
available in the __BasalClassicalHeatmap__ package: the original list 
from Moffitt et al. 2015; the 
updated list from Miyabayashi et al. 2020 and the list from 
Tiriac et al. 2018 that has been developed for pancreatic ductal 
adenocarcinoma (PDAC) organoids.


## Authors ##

[Astrid Desch&ecirc;nes](http://ca.linkedin.com/in/astriddeschenes "Astrid Desch&ecirc;nes"),
Daniel King and
David A. Tuveson


## Citation ##

If you use this package for a publication, we would ask you 
to cite the following:

> DeschĂȘnes A, King D and Tuveson DA. BasalClassicalHeatmap: Heatmap using basal-like and classical gene list and RNA-seq expression data. R package version 0.0.3, https://adeschen.github.io/BasalClassicalHeatmap/ 
  
You can also replace the latest by the Research Resource Identifier __(RRID)__, as 
example:

>   BasalClassicalHeatmap version 0.0.3, RRID: SCR_022949

If you use one of the available Basal-like/Classical gene list, the appropriate
paper should be referenced.

For Moffitt et al. 2015

> Moffitt RA, Marayati R, Flate EL et al. Virtual microdissection identifies distinct tumor- and stroma-specific subtypes of pancreatic ductal adenocarcinoma. Nat Genet. 2015 Oct;47(10):1168-78. doi: 10.1038/ng.3398. Epub 2015 Sep 7. PMID: 26343385; PMCID: PMC4912058.

For Tiriac et al. 2018

> Tiriac H, Belleau P, Engle DD et al. Organoid Profiling Identifies Common Responders to Chemotherapy in Pancreatic Cancer. Cancer Discov. 2018 Sep;8(9):1112-1129. doi: 10.1158/2159-8290.CD-18-0349. Epub 2018 May 31. PMID: 29853643; PMCID: PMC6125219.

For Miyabayashi et al. 2020

> Miyabayashi K, Baker LA, DeschĂȘnes A et al. Intraductal Transplantation Models of Human Pancreatic Ductal Adenocarcinoma Reveal Progressive Transition of Molecular Subtypes. Cancer Discov. 2020 Oct;10(10):1566-1589. doi: 10.1158/2159-8290.CD-20-0133. Epub 2020 Jul 23. PMID: 32703770; PMCID: PMC7664990.


## Documentation ##

[BasalClassicalHeatmap Website](https://adeschen.github.io/BasalClassicalHeatmap/)

[BasalClassicalHeatmap Get Started](https://adeschen.github.io/BasalClassicalHeatmap/articles/BasalClassicalHeatmap.html)

## Installation ##

To install the latest version accessible using the [devtools](https://cran.r-project.org/web/packages/devtools/index.html) 
package:

     ## Load required package
     library(devtools)

     ## Install the latest version of BasalClassicalHeatmap
     devtools::install_github('adeschen/BasalClassicalHeatmap')



## Maintainer

[Astrid Desch&ecirc;nes](https://github.com/adeschen/ "Astrid Desch&ecirc;nes")


## Bugs/Feature requests ##

[Please contact us](https://github.com/adeschen/BasalClassicalHeatmap/issues) for bug fixes or with feature requests. 

Thanks!

