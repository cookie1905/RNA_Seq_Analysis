# RNA-Seq Practice Example

This repository contains an example RNA-seq analysis pipeline for practice purposes.

## Dataset
- Species: **Human**
- Samples: **4 treatment vs 4 control**
- Only **chromosome 19** is mapped
- Input: **Gene-by-sample count matrix**

## Downstream Analyses
1. **Differential Expression Analysis**  
   Identify genes that are up- or down-regulated between treatment and control.

2. **Pathway/Functional Enrichment Analysis**  
   Explore enriched pathways or biological functions based on the differentially expressed genes.

## Notes
- This example is meant for practice and demonstration of typical RNA-seq workflows.
- All analyses start from count data; raw FASTQ processing is not included.

![Alt text](images/pca_plot.png)
![Alt text](images/diff_heatmap.png)
![Alt text](images/ggplot_volcano.png)
![Alt text](images/go_barplot.png)
![Alt text](images/gsea_dotplot.png)
