# scRNAseq-tutorial-MMG3003Y
Seurat-based scRNA-seq tutorial from MMG3003Y with annotated code and plots

This repository contains a personalized and annotated walkthrough of a guided Seurat tutorial from MMG3003Y (Genomics Methodologies) at the University of Toronto. The goal was to explore key steps in single-cell RNA-seq (scRNA-seq) analysis using real biological metadata and dimensionality reduction, clustering, and expression visualization.

## 🧬 Dataset

- Downsampled version of the Seattle Alzheimer’s Disease Brain Cell Atlas (SEA-AD)
- Samples from the middle temporal gyrus (MTG), labeled by cognitive status and AD progression score

## 📁 Included Files

- `annotated_scrnaseq_seurat_notes.Rmd`: My personal annotated walkthrough of the Seurat pipeline
- `figures/sc_violin_qc.png`: Violin plot showing QC metrics (nFeature, nCount, mitochondrial%)
- `figures/umap_clusters.png`: UMAP plot of clustered cells with Seurat cluster IDs
- `figures/feature_plot_top10.png`: FeaturePlot of top 10 variable genes across clusters

## 🧰 Tools Used

- R, Seurat, SCTransform
- PCA, UMAP, Louvain clustering
- Feature and violin plots with ggplot2

## 📌 Notes

This work was adapted from in-class materials for personal learning and portfolio purposes. All code and reflections are original. 
