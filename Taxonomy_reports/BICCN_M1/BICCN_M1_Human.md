---
title: "BICCN Human"
layout: single
classes: wide
author_profile: true
author: ReportCards
---

# Report card for `Correlation, Tree, and Seurat Mapping` on `Human motor cortex (Zemke et al. 2023)`

### Overview

A taxonomy was initially built using the BICCN's human motor cortex single nucleus 10x Multiome dataset. Subsequently, the dataset was mapped to itself, termed self-projection, for evaluating the ideal performances of correlation, tree, and seurat mapping algorithms.

### Quantitative analysis

The analysis evaluates the predictions of `correlation`, `tree`, and `Seurat` mappings in determining cluster labels in a self-projection evaluation.

Annotaion | F1-score
--- | ---
Cluster Correlation Mapping | 0.782
Cluster Tree Mapping | 0.758
Cluster Seurat Mapping | 0.981

## Correlation Mapping 

1. Label-wise F1-score<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/human/human_corr_figure_3.png"/>

2. Confidence values for correctly and incorrectly assigned labels<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/human/human_corr_figure_4.png"/>

3. Confusion matrix (row-normalized)<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/human/human_corr_figure_5.png"/>

## Tree Mapping 

1. Label-wise F1-score<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/human/human_tree_figure_3.png"/>

2. Confidence values for correctly and incorrectly assigned labels<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/human/human_tree_figure_4.png"/>

3. Confusion matrix (row-normalized)<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/human/human_tree_figure_5.png"/>

## Seurat mapping

1. Label-wise F1-score<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/human/human_seurat_figure_3.png"/>

2. Confidence values for correctly and incorrectly assigned labels<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/human/human_seurat_figure_4.png"/>

3. Confusion matrix (row-normalized)<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/human/human_seurat_figure_5.png"/>

