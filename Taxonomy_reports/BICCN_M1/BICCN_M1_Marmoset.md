---
title: "BICCN Marmoset"
layout: single
classes: wide
author_profile: true
author: ReportCards
---

# Report card for `Correlation, Tree, and Seurat Mapping` on `Marmoset motor cortex (Zemke et al. 2023)`

### Overview

A taxonomy was initially built using the BICCN's marmoset motor cortex single nucleus 10x Multiome dataset. In building the taxonomy, 1000 binary marker genes were selected based on their gene expression from the single-cell transcriptome. Subsequently, the dataset was mapped to itself, termed self-projection, for evaluating the ideal performances of correlation, tree, and seurat mapping algorithms.

### Quantitative analysis

The analysis evaluates the predictions of `correlation`, `tree`, and `Seurat` mappings in determining cluster labels in a self-projection evaluation.

Annotaion | F1-score
--- | ---
Cluster Correlation Mapping | 0.761
Cluster Tree Mapping | 0.711
Cluster Seurat Mapping | 0.972

## Correlation Mapping 

1. Label-wise F1-score<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/marmoset/marmoset_corr_figure_3.png"/>

2. Confidence values for correctly and incorrectly assigned labels<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/marmoset/marmoset_corr_figure_4.png"/>

3. Confusion matrix (row-normalized)<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/marmoset/marmoset_corr_figure_5.png"/>

## Tree Mapping 

1. Label-wise F1-score<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/marmoset/marmoset_tree_figure_3.png"/>

2. Confidence values for correctly and incorrectly assigned labels<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/marmoset/marmoset_tree_figure_4.png"/>

3. Confusion matrix (row-normalized)<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/marmoset/marmoset_tree_figure_5.png"/>

## Seurat mapping

1. Label-wise F1-score<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/marmoset/marmoset_seurat_figure_3.png"/>

2. Confidence values for correctly and incorrectly assigned labels<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/marmoset/marmoset_seurat_figure_4.png"/>

3. Confusion matrix (row-normalized)<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/marmoset/marmoset_seurat_figure_5.png"/>

</details>
