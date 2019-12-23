---
layout: article
---

Here you can find the scientific software packages and data analysis workflows that we have published.

## R packages

### [wiggleplotr](https://bioconductor.org/packages/release/bioc/html/wiggleplotr.html)

wiggleplotr is a Bioconductor package for making RNA-seq read coverage plots from BigWig files. A key advantage of wiggleplotr is that introns of long transcripts can be rescaled to a fixed length, enabling better visualisation of exonic read coverage.

### [txrevise](https://github.com/kauralasoo/txrevise)
txrevise is a tool to convert Ensembl transcript annotations into distinct sets of transcriptional events: alternative promoters, splicing events and alternative 3′ ends. These event annotations can subsequently used to detect differences in transcript usage between biological conditions or identify transcript usage QTLs. Read more from the [paper](https://doi.org/10.7554/eLife.41673.001) or the see the [vignette](http://htmlpreview.github.io/?https://github.com/kauralasoo/txrevise/blob/master/inst/doc/construct_events.html) for a worked out example. The pre-computed event annotations can be directly downloaded from [Zenodo](https://doi.org/10.5281/zenodo.3232932) and our RNA-seq quantifcation pipeline ([kerimoff/rnaseq](https://github.com/kerimoff/rnaseq)) implements txrevise as one of the optional quantification methods.  

## Analysis workflows

### [kerimoff/rnaseq](https://github.com/kerimoff/rnaseq)

### [kerimoff/qtlmap](https://github.com/kerimoff/rnaseq)