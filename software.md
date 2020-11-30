---
layout: article
---

## Analysis workflows

We are developing and maintaining a number of modular data analysis workflows for the [eQTL Catalogue](https://www.ebi.ac.uk/eqtl/) project.

* [eQTL-Catalogue/genimpute](https://github.com/eQTL-Catalogue/genimpute) - genotype phasing and imputation
* [eQTL-Catalogue/rnaseq](https://github.com/eQTL-Catalogue/rnaseq) - RNA-seq quantification
* [eQTL-Catalogue/qcnorm](https://github.com/eQTL-Catalogue/qcnorm) - RNA-seq normalisation and quality control
* [eQTL-Catalogue/qtlmap](https://github.com/eQTL-Catalogue/qtlmap) - eQTL analysis
* [eQTL-Catalogue/susie-workflow](https://github.com/eQTL-Catalogue/susie-workflow) - statistical fine mapping

Click [here](https://github.com/eQTL-Catalogue/eQTL-Catalogue-resources/blob/master/tutorials/workflow_execution.md) to learn how these workflows are used to process data for the eQTL Catalogue.

## R packages

### [wiggleplotr](https://bioconductor.org/packages/release/bioc/html/wiggleplotr.html)

wiggleplotr is a Bioconductor package for making RNA-seq read coverage plots from BigWig files. A key advantage of wiggleplotr is that introns of long transcripts can be rescaled to a fixed length, enabling better visualisation of exonic read coverage.

### [txrevise](https://github.com/kauralasoo/txrevise)
txrevise is a tool to convert Ensembl transcript annotations into distinct sets of transcriptional events: alternative promoters, splicing events and alternative 3′ ends. These event annotations can subsequently used to detect differences in transcript usage between biological conditions or identify transcript usage QTLs. Read more from the [paper](https://doi.org/10.7554/eLife.41673.001) or the see the [vignette](http://htmlpreview.github.io/?https://github.com/kauralasoo/txrevise/blob/master/inst/doc/construct_events.html) for a worked out example. The pre-computed event annotations can be directly downloaded from [Zenodo](https://doi.org/10.5281/zenodo.3232932) and our RNA-seq quantifcation pipeline ([eQTL-Catalogue/rnaseq](https://github.com/eQTL-Catalogue/rnaseq)) implements txrevise as one of the optional quantification methods.  

