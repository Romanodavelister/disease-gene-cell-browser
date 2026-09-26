# UCSC Cell Browser Activity

# Assigned Gene and Disease

**Gene**: Coagulation Factor V (F5)

**Disease**: Factor V Leiden thrombophilia (activated protein C resistance). The F5 c.1601G>A (p.Arg534Gln) variant affects the Factor V protein and reduces its normal inactivation by activated protein C, which can increase the tendency to form abnormal blood clots.

# Organ/Tissue Choice and Dataset Information

**Organ / Tissue:** Human Fetal Liver

**Dataset Name:** Fetal Liver

**Dataset Scale:** Approximately 113,000 cells, representing single-cell transcriptome data from human fetal liver cells and providing information about different cell populations involved in fetal liver haematopoiesis.

**Why this organ/tissue is relevant to your assigned gene/disease**: The fetal liver is relevant to F5 because the liver produces most of the coagulation Factor V protein encoded by the F5 gene. Factor V is an important component of the blood-clotting pathway affected in Factor V Leiden thrombophilia.

# Understanding the Cell Map

**a. What type of visualization is being shown?** UMAP (Uniform Manifold Approximation and Projection).

**b. What does one dot represent?** Each dot represents one measured cell in the single-cell dataset.

**c. What do the clusters represent in this particular dataset?** The clusters represent different cell types or cell populations found in the human fetal liver, based on their gene-expression profiles.

**d. List at least three cell-type or cluster labels visible in the dataset.**

1. Hepatocyte
2. Kupffer Cell
3. Endothelial cell

# Assigned Gene Expression

**a. Assigned gene symbol:** F5

**b. Dataset used:** Fetal Liver and Yolk Sac – Fetal Liver (Decoding human fetal liver haematopoiesis)

**c. Is expression widespread, restricted, or low/undetected?** F5 expression is generally low/undetected and appears restricted to a small number of cells. The expression legend shows that about 97.6% of cells have an expression value of 0, supporting this observation.

**d. Which cluster(s) appear to contain cells with stronger expression?** The Hepatocyte cluster shows the clearest stronger F5 expression, with some detectable expression also visible around the VCAM1+ EI macrophage cluster.

**e. Which cluster(s) appear to contain little or no detectable expression?** Little or no detectable F5 expression is visible across most of the other clusters, including the large Early/Mid/Late Erythroid populations and many immune/progenitor clusters.

# Cell Types and Clusters

**a. Cell type/cluster with the strongest visible expression:** Hepatocyte

**b. Another cell type/cluster with detectable expression:** Late Erythroid / Erythroid-associated cells show some detectable expression.

**c. Cell type/cluster with relatively low or undetected expression:** Endothelial cells show relatively low/undetected F5 expression compared with hepatocytes. Many immune-cell clusters also show little to no visible expression.

**d. Is the expression pattern broad or cell-type restricted?** Cell-type restricted, with the strongest visible expression concentrated in the Hepatocyte cluster.

**e. Biological explanation (2–3 sentences):** Based on the selected fetal liver dataset, F5 expression appears to be concentrated mainly in hepatocytes, which is consistent with the liver being an important site of coagulation factor production. The lower expression in most other cell clusters suggests that F5 is more associated with hepatocyte function than with the major immune and blood-cell populations represented in this dataset.

# Expression plot

**a. Which cells/cluster did you select?** Hepatocytes, compared with the other visible cell clusters.

**b. Does your selected group show higher, lower, or similar expression compared with the comparison cells?** The hepatocyte group shows higher F5 expression than the comparison cells.

**c. What does the expression plot add that was not obvious from the UMAP/t-SNE map?** The expression plot shows the distribution and relative level of F5 expression more clearly than the UMAP alone. While the UMAP shows where expression is located, the plot helps confirm that expression is concentrated at higher levels in the selected hepatocyte group rather than being broadly expressed across all cells.

# Marker Genes

**a. Cluster/cell type examined:** Hepatocyte  

**b. Marker gene 1:** APOA2  

**c. Marker gene 2:** APOA1  

**d. Marker gene 3:** AMBP

**e. Does your assigned gene behave like a cell-type marker in this dataset? Explain briefly.** No, F5 does not behave like a cell-type marker in this dataset. It is not listed among the top cluster markers for Hepatocytes, which are characterized by much higher z-scores (z > 70) like APOA2 and APOA1.

# Disease Gene vs. Marker Gene
