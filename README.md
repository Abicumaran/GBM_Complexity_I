# GBM_Complexity_I
Codes for Single-cell analysis in GBM transcriptional dynamics

This Github Respository corresponds to all codes, tutorials, packages, and tutorials required for the single-cell data analysis from our iScience paper on GBM Cell Fate/Gene Expression Dynamics.

Citation:

Uthamacumaran, A. and Craig, M. Algorithmic Reconstruction of Glioblastoma Network Complxity. iScience (2022). 
https://doi.org/10.1016/j.isci.2022.104179



DATASET INSTRUCTIONS

See iScience publication for durther details.

See the .txt file or Word document for code instructions. The single-cell datasets (count matrix) are available at the following repositories:

https://singlecell.broadinstitute.org/single_cell/study/SCP393/single-cell-rna-seq-of-adult-and-pediatric-glioblastoma#study-summary

DOI: 10.1016/j.cell.2019.06.024. GEO: GSE131928

https://singlecell.broadinstitute.org/single_cell/study/SCP503/gradient-of-developmental-and-injury-reponse-transcriptional-states-define-functional-vulnerabilities-underpinning-glioblastoma-heterogeneity#study-download

DOI: https://doi.org/10.1038/s43018-020-00154-9

Note: For the Seurat clustering, you can choose to analyze higher number of PCA loadings. However, for the results we used top 10 PCA loadings only.
Change the directories in the scEpath code as appropriate (e.g., for the Rscript). The gene expression matrix was saved as "input_data.txt" in the folder
and added to path when running the code.

Title: Algorithmic Reconstruction of Glioblastoma Network Complexity

Authors: Abicumaran Uthamacumaran and Morgan Craig

