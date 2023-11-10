---
title: "Cross-areal S1"
layout: single
classes: wide
author_profile: true
author: ReportCards
---

# Report card for `Correlation and Tree Mapping` on `Somatosensory (S1) neocortical area (Jorstad et al. 2023)`

### Overview

A taxonomy was initially built using the Somatosensory (S1) neocortical area single nucleus dataset. In building the taxonomy, 1000 binary marker genes were selected based on their gene expression from the single-cell transcriptome. Subsequently, the dataset was mapped to itself, termed self-projection, for evaluating the ideal performances of correlation and tree mapping algorithms.

### Quantitative analysis

The analysis evaluates the predictions of `correlation` and `tree` mappings in determining cluster labels in a self-projection evaluation.

Annotaion | F1-score
--- | ---
Cluster Correlation Mapping |0.785
Cluster Tree Mapping | 0.737

## Correlation Mapping 

1. Label-wise F1-score<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/crossareal/s1/s1_corr_figure_1.png"/>

2. Confidence values for correctly and incorrectly assigned labels<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/crossareal/s1/s1_corr_figure_2.png"/>

3. Confusion matrix (row-normalized)<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/crossareal/s1/s1_corr_figure_3.png"/>

## Tree Mapping 

1. Label-wise F1-score<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/crossareal/s1/s1_tree_figure_1.png"/>

2. Confidence values for correctly and incorrectly assigned labels<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/crossareal/s1/s1_tree_figure_2.png"/>

3. Confusion matrix (row-normalized)<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/crossareal/s1/s1_tree_figure_3.png"/>
