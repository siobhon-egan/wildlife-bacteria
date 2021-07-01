# Wildlife bacteria

A [workflowr](https://github.com/jdblischak/workflowr) project for Siobhon Egan's PhD project on the characterisation of bacteria from wildlife ticks, tissue and blood.

Project website: http://siobhonlegan.com/wildlife-bacteria/

In the spirit of reproducibility this project website is created that outlines analysis done for the following publication:

*The bacterial biome of ticks and their wildlife hosts at the sylvatic urban interface.* 

**Authors**: Siobhon L. Egan, Casey L. Taylor, Peter B. Banks, Amy S. Northover, Liisa A. Ahlstrom, Una M. Ryan, Peter J. Irwin, Charlotte L. Oskam. 

This publication is also a chpater of my PhD Thesis 2021

## Data availbility

Raw Illumina MiSeq data is available at European nucleotide archive the project accession number PRJEB46006 (ERP130188), which includes the following sample accession numbers:

- 16S bacteria blood ERS6632201--ERS6632359
- 16S bacteria tissue ERS6632360--ERS6632531
- 16S bacteria tick ERS6633094--ERS6633353

Nucleotide sequence data available on Genbank

Anaplasmataceae (long 16S rRNA) 
`MW633160-MW633167`

Borrelia 16S rRNA
`MW633074`

Bartonella ITS
`MW633076-MW633082`

ASVs for taxa of interest
`XXXXXX-XXXXXX`

## Supporting data

Data used but not directly produced for this manuscript.

Nucleotide data for identification of ticks
MW665133-MW665150

## Directory information


# Worlflowr commands 

To build/view webiste locally
`wflow_build()` and `wflow_view()`

Status of workflow
`wflow_status()`

Publish website pages
`wflow_publish(c("analysis/index.Rmd", "analysis/first-analysis.Rmd"), "Add my first analysis")`

Push website to github
`wflow_git_push()`
