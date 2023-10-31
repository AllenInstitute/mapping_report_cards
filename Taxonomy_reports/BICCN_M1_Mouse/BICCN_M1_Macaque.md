<details>
<summary> Cluster level metrics - Correlation mapping: </summary>

1. Label-wise F1-score<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/macaque/macaque_corr_figure_3.png"/>

2. Confidence values for correctly and incorrectly assigned labels<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/macaque/macaque_corr_figure_4.png"/>

3. Label-wise recall<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/macaque/macaque_corr_figure_2.png"/>

4. Label-wise precision<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/macaque/macaque_corr_figure_1.png"/>

5. Confusion matrix (row-normalized)<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/macaque/macaque_corr_figure_5.png"/>

</details>


<details>
<summary> Cluster level metrics - Tree mapping: </summary>

1. Label-wise F1-score<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/macaque/macaque_tree_figure_3.png"/>

2. Confidence values for correctly and incorrectly assigned labels<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/macaque/macaque_tree_figure_4.png"/>

3. Label-wise recall<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/macaque/macaque_tree_figure_2.png"/>

4. Label-wise precision<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/macaque/macaque_tree_figure_1.png"/>

5. Confusion matrix (row-normalized)<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/macaque/macaque_tree_figure_5.png"/>

</details>

<details>
<summary> Cluster level metrics - Seurat mapping: </summary>

1. Label-wise F1-score<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/macaque/macaque_seurat_figure_3.png"/>

2. Confidence values for correctly and incorrectly assigned labels<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/macaque/macaque_seurat_figure_4.png"/>

3. Label-wise recall<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/macaque/macaque_seurat_figure_2.png"/>

4. Label-wise precision<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/macaque/macaque_seurat_figure_1.png"/>

5. Confusion matrix (row-normalized)<br>
<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../../assets/biccn/macaque/macaque_seurat_figure_5.png"/>

</details>

### Sequencing technology effect analysis

Here we evaluate `Heirarchical Correlation Mapping` at correctly predicting the Subclass label for multiple sequencing technologies.

Query | Annotation | F1-score | | Annotation | F1-score          
--- | --- | --- | --- | --- | ---                  
10X_cells_v3_AIBS | Subclass | 0.972 | | Cluster | 0.857     
10X_nuclei_v3_AIBS | Subclass | 0.943 | | Cluster | 0.785
10X_nuclei_v3_Broad | Subclass | 0.966 | | Cluster | 0.854
10X_cells_v2_AIBS | Subclass | 0.976 | | Cluster | 0.855
10X_nuclei_v2_AIBS | Subclass | 0.918 | | Cluster | 0.650
SmartSeq_cells_AIBS | Subclass | 0.971 | | Cluster | 0.812
SmartSeq_nuclei_AIBS | Subclass | 0.961 | | Cluster | 0.803

<img align='center' style="padding:10px 0px 10px 0px; border-radius: 0%" src="../assets/Mouse_WB/HANN/Ground_truth_subclass_HANN_WB_subclass_cond_conf_box.png"/>

### Recommendations and caveats
 - At the **Class**, **Neighborhood**, and **Subclass** level, for high quality RNA-seq data - `Heirarchical Correlation Mapping` makes few errors.
 - `Heirarchical Correlation Mapping` mapping robustly classify samples from multiple sequencing techologies which lead to changes in gene expression.
