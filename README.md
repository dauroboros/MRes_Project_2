# MRes_Project_2
Project on B cell immune landscape in Prostate Cancer, Daur Meretukov, 2024

This repository stores R studio project files to run step-by-step data analysis pipeline for MRes Project 2 using pre-downloaded data.

This project consists of 3 parts:

Part 1. Filename: MRes2_part_1.Rmd

This file contains code to create the following plots: Heatmap with xCELL results for all samples + cell subtypes based on CD biomarkers expression + overall survival data; Kaplan-Meier plots for B cell subtypes survival analysis (high and low abundances); Cox proportional Hazards Model for multivariative analysis of B cell subtypes and overall survival; Group Comparisons for Class-switched and pro B cells across all tumor sites and molecular clusters;

Part 2. Filename: MRes2_part_2.Rmd

This file contains code for Immunarch and related analysis of B cell data, and includes several steps: subset clones into variable IG genes from data, plot CDR3 length among samples, calculate and visualise number of clonotypes, IGHV group comparison across tumor sites and clusters; diversity estimation across tumor sites and clusters; 

Part 3. Filename: MRes2_part_3.Rmd

This file contains code to create the following plots: prostate cancer subtypes heatmap on a basis of consensus clustering using RNAseq data, PCA analysis for this data, pathway enrichment analysis (GSEA) associated with subtypes, correlation analysis between B cell subtypes, CD biomarkers and hallmarks of cancer.
