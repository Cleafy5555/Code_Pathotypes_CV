# Pathotypes, production risk, and isolate metabolomics

Annotated R scripts from the working scripts used for the paper "INTEGRATION OF PRODUCTION OUTCOMES AND EARLY ROOT METABOLOMIC SIGNATURES IDENTIFIES ISOLATE-SPECIFIC IMPACT OF PLASMODIOPHORA BRASSICAE ON CROP PHYSIOLOGY" and Chapter 5 of my thesis.

## Scope
This repository covers:
- plant-level production-risk phenotyping and the severity–danger matrix
- publication and supplementary figure generation for the phenotyping chapter
- metabolomics preprocessing from MS-DIAL exports
- PCA-based isolate/batch visualisation and links between metabolomic divergence and danger scores
- representative PCA-loading feature plots and MetaboAnalyst export tables

## Important note
This repository contains cleaned and annotated analysis code only. Raw data are not included.


## Suggested script order
1. `01_danger_matrix_core.R`
2. `02_danger_matrix_figures.R`
3. `03_metabolomics_preprocessing_qc.R`
4. `04_metabolomics_pca_and_danger_link.R`
5. `05_pca_loading_features_and_metaboanalyst_exports.R`

