# GBM_Complexity_I
Codes for Single-cell analysis in GBM transcriptional dynamics

This Github Respository corresponds to all codes, tutorials, packages, and tutorials required for the single-cell data analysis from our paper on GBM Cell Fate/
Gene Expression Dynamics.

Title: Algorithmic Reconstruction of GBM Network Complexity

Authors: Abicumaran Uthamacumaran and Morgan Craig* (Supervisor)

BioRxiv Link to Paper: https://www.biorxiv.org/content/10.1101/2021.09.21.461255v1

doi: https://doi.org/10.1101/2021.09.21.461255

Currently Under Review: Journal of Translational Medicine (BMC)

See the .txt file or Word document for code instructions. The single-cell datasets (count matrix) are available at the following repositories:

https://singlecell.broadinstitute.org/single_cell/study/SCP393/single-cell-rna-seq-of-adult-and-pediatric-glioblastoma#study-summary

DOI: 10.1016/j.cell.2019.06.024. GEO: GSE131928

https://singlecell.broadinstitute.org/single_cell/study/SCP503/gradient-of-developmental-and-injury-reponse-transcriptional-states-define-functional-vulnerabilities-underpinning-glioblastoma-heterogeneity#study-download

DOI: https://doi.org/10.1038/s43018-020-00154-9

Note: For the Seurat clustering, you can choose to analyze higher number of PCA loadings. However, for the results we used top 10 PCA laodings only.
Change the directories in the scEpath code as appropriate (e.g., for the Rscript). The gene expression matrix was saved as "inpu_data.txt" in the folder
and added to path when running the code.
