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

**a. Assigned disease gene:** F5


**b. Marker gene:** APOA2


**c. Which gene shows a more cell-type-restricted expression pattern?** APOA2 — it is a strong marker of the hepatocyte cell type.


**d. Which gene appears more broadly expressed?** F5 — compared with the hepatocyte marker APOA2, F5 can show expression beyond the most strongly defined hepatocyte marker pattern.


**e. What does this comparison teach you?** A disease-associated gene such as F5 is linked to a disease or biological condition but is not necessarily exclusive to one cell type. A cell-type marker gene such as APOA2 is useful for identifying a particular cell type because its expression is more strongly restricted to that cell population.

# Connection to Genome Browser and ClinVar

**1. Chromosome location:** Chromosome 1 (1q24.2). The F5 gene is located at cytogenetic band 1q24.2.


**2. Disease-associated variant examined previously:** Factor V Leiden (F5 c.1601G>A, p.Arg534Gln; historically p.Arg506Gln; rs6025). This is a missense variant that affects the activated protein C cleavage site of factor V and is associated with activated protein C resistance and increased risk of venous thromboembolism. 


**3. Cell type(s) expressing the gene in the current Cell Browser dataset:** F5 expression is most clearly observed in hepatocytes, with lower/detectable expression also visible in some other cell populations. The strongest visible expression in the provided fetal liver dataset is in the Hepatocyte cluster.


**4. Does the observed cell expression make biological sense?** Yes. Based on the selected fetal liver dataset, the strong F5 expression in hepatocytes makes biological sense because factor V is a coagulation protein produced primarily by the liver. The Factor V Leiden variant alters factor V function by affecting its regulation by activated protein C, which can contribute to excessive clotting. Therefore, the observed hepatocyte expression is consistent with the known function of F5, although this dataset itself does not show the effect of the specific variant.


**5. Can this single Cell Browser dataset prove that the gene causes the disease?** No. A Cell Browser expression dataset only shows where and/or how strongly a gene is expressed in the sampled cells; it does not establish that a particular gene variant causes a disease. Demonstrating disease causation requires additional evidence such as genetic/clinical data and functional studies showing how the specific F5 Factor V Leiden variant alters protein function and disease risk.

# Reflection 

**1. What did the UCSC Cell Browser show you that the UCSC Genome Browser could not?** The UCSC Cell Browser showed me where F5 is expressed among different cell types, especially the higher expression in hepatocytes. The Genome Browser mainly showed the gene's location, structure, and sequence information, but not the expression pattern at the individual cell or cell-cluster level.


**2. Why can the same gene have different expression levels among different cell types?** Different cell types have different functions, so they do not need to use all genes at the same level. Some genes are more active in certain cells because of differences in cell function and gene regulation.


**3. Why should you be careful when interpreting a gene that shows zero or very low expression in single-cell data?** Zero expression does not always mean that the gene is completely inactive in that cell. The amount of RNA captured can be affected by the limitations of single-cell sequencing, so some transcripts may simply not be detected.


**4. Why is it useful to combine information about genomic location, genetic variants, and cell-specific gene expression?** Combining these types of information gives a clearer picture of how a gene may be related to a disease. For F5, I could connect its chromosome location and Factor V Leiden variant with its expression mainly in liver cells, helping me understand the gene from both the genetic and cellular sides.


**5. What was the most interesting observation you made about your assigned gene?** The most interesting observation for me was that F5 showed its strongest visible expression in hepatocytes in the fetal liver dataset. This made sense because F5 produces a coagulation-related protein, so seeing it strongly expressed in liver cells connected the Cell Browser results with what I learned about Factor V.

# References and Links

UCSC Cell Browser: https://cells.ucsc.edu 
