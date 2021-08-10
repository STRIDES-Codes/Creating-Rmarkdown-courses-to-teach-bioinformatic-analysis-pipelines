# Creating-Rmarkdown-courses-to-teach-bioinformatic-analysis-pipelines


#The raw data includes information on 2,700 Peripheral Blood Mononuclear Cells #(PBMC) freely available from 10X Genomics that were sequenced on the Illumina #NextSeq 500 using Homo sapiens (human) genome assembly GRCh37 (hg19) as #reference. 

#install.packages("learnr")
#install.packages("dplyr")
#install.packages('Seurat')

library(learnr)
library(dplyr)
library(Seurat)
knitr::opts_chunk$set(echo = FALSE)



# Load the PBMC dataset
pbmc.data <- Read10X(data.dir = "../data/pbmc3k/filtered_gene_bc_matrices/hg19/")
require(data.table)


