# Creating-Rmarkdown-courses-to-teach-bioinformatic-analysis-pipelines

---
title: "Package ‘SeuratObject’"
output: learnr::tutorial
runtime: shiny_prerendered
---

The raw data includes information on 2,700 Peripheral Blood Mononuclear Cells (PBMC) freely available from 10X Genomics that were sequenced on the Illumina NextSeq 500 using Homo sapiens (human) genome assembly GRCh37 (hg19) as reference.

There are 13714 features across the 2700 samples within 1 single-cell RNA seq assay. 

#install.packages("learnr")
#install.packages("dplyr")
#install.packages('Seurat')
#install.packages('patchwork')
#install.packages("Rcpp")

library(learnr)
library(dplyr)
library(Seurat)
library(patchwork)



# Load the PBMC dataset
pbmc.data <- Read10X(data.dir = "~/Desktop/GDSSP/Codeathon_08.10/Creating-Rmarkdown-courses-to-teach-bioinformatic-analysis-pipelines/Descriptions/filtered_gene_bc_matrices/hg19/")

# Initialize the Seurat object with the raw (non-normalized data).
pbmc <- CreateSeuratObject(counts = pbmc.data, project = "pbmc3k", min.cells = 3, min.features = 200)
pbmc


