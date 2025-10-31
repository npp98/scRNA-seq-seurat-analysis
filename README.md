# Single-Cell RNA-seq Analysis of Mutant vs Wildtype Drosophila

[![Latest Release](https://img.shields.io/github/v/release/npp98/scRNA-seq-seurat-analysis)](https://github.com/npp98/scRNA-seq-seurat-analysis/releases/latest)

## 📊 View Analysis Report

**[📥 Download Complete HTML Report from Latest Release](https://github.com/npp98/scRNA-seq-seurat-analysis/releases/latest)**

The interactive HTML report includes all visualizations, statistical analyses, and biological interpretations.

## Description

This project analyzes single-cell RNA sequencing data from mutant and wild-type Drosophila samples in order to perform a differential expression analysis to identify differential gene expression patterns and cellular responses related to genetic mutation.

## Key Results

* **25,014 cells** analyzed across **10 distinct clusters**
* **866 significantly differentially expressed genes** identified
* The mutation causes gene downregulation with activation of cellular stress response mechanisms

## Getting Started

### Dependencies

* R (>= 4.0.0)
* RStudio
* Required R packages: Seurat, tidyverse, ggplot2, patchwork

### Installing

* Clone this repository or download from releases
* Ensure data files are located in `scRNA_analysis_Natalia_Pretel/data/sample_scRNA_sequencing_data/`

### Executing Program

* Open `scRNA_analysis.Rmd` in RStudio
* Run all code chunks sequentially or knit to HTML
* Results will be generated in the `results/` folder
* Expected runtime: ~10 minutes
* Success message: `=== The analysis has finished successfully ====`

## Analysis Workflow

1. **Quality Control**: Cell and gene filtering based on QC metrics
2. **Normalization**: Log-normalization and scaling
3. **Dimensionality Reduction**: PCA and UMAP visualization
4. **Clustering**: Identification of 10 distinct cell populations
5. **Differential Expression**: Statistical comparison between mutant and wildtype
6. **Visualization**: Comprehensive plotting of results

## Repository Contents

* `scRNA_analysis.Rmd` - R Markdown source code for complete analysis
* `scRNA_analysis.html` - Rendered HTML report (download from [Releases](https://github.com/npp98/scRNA-seq-seurat-analysis/releases/latest))
* `results/` - Output files, figures, and differential expression tables
* `data/` - Input scRNA-seq data files

## Files Generated

* **QC and visualization plots** (10 figures saved to `results/figures/`)
* **Differential Expression Tables** (3 CSV files)
* **Processed Seurat Object** for further analysis
* **Session information** for reproducibility

## Author

**Natalia Pretel Pretel**  
Master's Student in Bioinformatics  
Northeastern University  
📧 pretel.n@northeastern.edu

## Version History

* **v1.0.0** (Latest)
    * Complete single-cell RNA-seq analysis workflow
    * Differential expression analysis between mutant and wildtype
    * Comprehensive visualization and interpretation
* **v0.1**
    * Initial Release

## Acknowledgments

* Perrimon Lab at Harvard Medical School for providing dataset and assignment framework
* Analysis performed using Seurat package and R ecosystem
