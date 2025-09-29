# scRNA-seq-seurat-analysis
Comprehensive scRNA-seq analysis workflow in R using Seurat package: quality control, normalization, dimensionality reduction, clustering, and differential expression analysis

# Single-Cell RNA-seq Analysis of Mutant vs Wildtype Drosophila
##Date: September 2025

## Description

This projects analyzes single-cell RNA sequencing data from mutant and wildtype Drosophila samples in order to perform a differential expression analysis to identify differential gene expression patterns and cellular responses related to genetic mutation. 

## Getting Started

### Dependencies

* R (> 4.0.0)
* Required R packages: Seurat, tidyverse, ggplot2, patchwork
* Rstudio

### Installing

* The repository will be contained in the scrRNA_analysis_Natalia_Pretel.zip
* In order to execute them, we will have to decompress the zip and ensure that the data files are in scrRNA_analysis_Natalia_Pretel/data/sample_scRNA_sequencing_data/

### Executing program

* Open `scRNA_analysis.Rmd` in RStudio.
* Run all the code chuncks sequentially or knit to HTML.
* Results will be generated in `results/` folder.
* The expected runtime is ~10 minutes, and it will display the message `=== The analysis has finished succesfully ====` when finished. 

## Key results

* There were 25.014 cells analyzed across 10 different clusters.
* There were 866 significantly differentially expressed genes identified.
* The mutation causes gene downregulation with an activation of the cellular stress response mechanisms.  


## Authors

Natalia Pretel Pretel

pretel.n@northeastern.edu

## Version History

* 0.1
    * Initial Release

## Files Generated

* QC and visualization plots (10 items)
* Differential Expression Tables ( 3 CSV files)
* A processed Seurat Object for further analysis
* The session information for reproducibility

## Help

* All the plots are automatically saved to results/figures/


## Acknowledgments

* Perrimon Lab for providing dataset and assignment framework. 
