---
title: ""
layout: single
classes: wide
author_profile: true
author: ReportCards
---

## Overview

Detailed model evaluation on curated benchmark datasets are stored here to inform users about mapping algorithm biases and accuracies at mapping cell type labels using Allen Institute taxonomies as references.

## Evaluations: `Hierarchical Correlation Mapping (HANN)`

Model | Benchmark | Runtime 
--- | --- | --- 
[HANN](Mouse_reports/HANN_mouse_WB.md) | mouse WB | 0.76 Hours 
[HANN](Human_reports/HANN_human.md)    | human MTG SEA-AD | 3 Hours 

<!-- ## Evaluations: `Hierarchical Correlation Mapping with Finding Markers (HANN (FindMarkers))`

Model | Benchmark | Runtime 
--- | --- | --- 
[HANN (FindMarkers)](Mouse_reports/HANN_FindMarkers_mouse_WB.md) | mouse WB | 17.41 Hours 
[HANN (FindMarkers)](Human_reports/HANN_FindMarkers_human.md)    | human MTG SEA-AD | 3 Hours  -->

## Evaluations: `Correlation Mapping (CORR)`

Model | Benchmark | Runtime 
--- | --- | --- 
[CORR](Human_reports/FLAT_human.md)    | human MTG SEA-AD | 1.8 Hours 
[CORR](Mouse_reports/FLAT_mouse_WB.md) | mouse WB | 0.36 Hours 

## Taxonomy Evaluations: `Correlation, Tree, and Seurat Mappings`

[Taxonomies](taxonomies)

## Benchmarks
More details about the benchmark data can be found [here](LINK). (Link broken until data cards setup)

## Algorithms
More details about the models benchmarked can be found [here](LINK). (Link broken until model cards setup)

## Scripts
The python scripts to produce the model report cards are hosted on the Allen Institute bmark repo.
