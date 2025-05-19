# Pancreatic Cell Type Clustering from scRNA-seq Data

Midterm project for STAT 646 at Texas A&M University. The goal is to process, cluster, annotate, and integrate single-cell RNA sequencing (scRNA-seq) data from two studies:

- Segerstolpe et al. (Smart-seq2)
- Baron et al. (inDrop)

## Objectives

- Normalize and preprocess scRNA-seq data
- Perform dimensionality reduction (PCA, UMAP)
- Visualize expression of marker genes
- Annotate and cluster cells by type
- Compare datasets and correct for batch effects using CCA

## Marker Genes

- Ductal (KRT19), Acinar (PRSS1)
- α (GCG), β (INS), γ (PPY), δ (SST), ϵ (GHRL)

## Repository Structure

- `scripts/`: Main R script for the entire pipeline
- `reports/`: Compiled PDF of midterm submission
- `data/`: External data source links
- `figures/`: Optional visualizations (FeaturePlot, UMAP, etc.)

## Data Sources

Due to size, raw datasets are not included:
- [Segerstolpe Dataset](https://www.ebi.ac.uk/biostudies/arrayexpress/studies/E-MTAB-5061)
- [Baron Dataset](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE84133)

## Requirements

See `requirements.txt` for R packages used.

## License

MIT License
