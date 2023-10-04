# Kron Cohort 77 Differential Expression Analysis

This repository contains all code used for the  analysis of gene differential expression results *Aplysia californica* sensory neurons and orthology of genes in *Aplysia californica* to those of humans with special focus on genes of interest for Alzheimer's Disease. This analysis was performed in the lab of Dr. Lynne Fieber at the University of Miami Rosenstiel School of Marine and Atmospheric Science.  This repository consists mainly of the R project hierarchy and associated files and scripts used  during this analysis.


The associated publication can be found here:  
Kron NS, Fieber LA. Aplysia Neurons as a Model of Alzheimer's Disease: Shared Genes and Differential Expression. J Mol Neurosci. 2022 Feb;72(2):287-302. doi: 10.1007/s12031-021-01918-3. Epub 2021 Oct 18. PMID: 34664226; PMCID: PMC8840921.
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8840921/

Author: Nicholas Kron - n.kron@umiami.edu  
Maintainer: Nicholas Kron - n.kron@umiami.edu  

## File hierarchy overview:
data: directory for data used in downstream R analysis  
--annotation_data : raw annotation files for building annotation objects in R for downstream analysis  
--metadata : metadata on animals, RNA extractions, and samples used in downstream R analysis  
--r_data : destination for storage of intermediate R data. (not presents as listed in the gitignore file)  
scripts: scripts used for data analysis in this study
