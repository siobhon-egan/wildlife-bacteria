# Wildlife bacteria

A [workflowr](https://github.com/jdblischak/workflowr) project for Siobhon Egan's PhD project on the characterisation of bacteria from wildlife ticks, tissue and blood.

Project website available here http://siobhonlegan.com/wildlife-bacteria/

Bacterial profiling of wildlife samples.

In the spirit of reproducibility this project website is created that outlines analysis done for the following publication:

Egan et al. Uncovering sylvatic cylces of bacteria in Australian wildlife. 

PhD Thesis 2021 (Chapter three)

## Data availbility

Raw Illumina MiSeq data is available at NCBI SRA project XXXXX

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
