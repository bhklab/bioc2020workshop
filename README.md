# Biomarker discovery from high throughput screening datasets

## Instructor(s) name(s) and contact information

* Petr Smirnov <petr.smirnov@uhnresearch.ca>
* Arvind Mer <arvind.mer@uhnresearch.ca>
* Christopher Eeles <christopher.eeles@uhnresearch.ca>


## Workshop Description

This workshop will focus on the synergies between analysis results from the PharmacoGx, Xeva and RadioGx packages and their usefulness for discovery of biomarkers of drug and/or radiation sensitivity in cancer cell lines (CCLs) and patent derived xenograft models (PDXs). We will discuss issues with data curation, consistency and reproducibility within the literature as well as illustrate the importance of unified analytical platforms, data and code sharing in bioinformatics and biomedical research. In this lab learners will be led through an analysis for each of the three packages on data provided by the download functions within them. The results of these analyses will then be explored to highlight how drug and radiation dose-response profiles in CCLs and PDXs can be used to discover potential synergistic biomarkers for drug-radiation and drug combination therapies. The resulting biomarkers will be discussed in the context of translational cancer research and clinical applications of genomic data. We will conclude with a discussion of how these biomarkers can be used to inform future in vitro and in vivo treatment screenings and ultimately provide useful insights for clinical trial design. 

### Pre-requisites


* Basic knowledge of R syntax
* Knowledge of or interest in pharmacogenomics and radio-genomics
* Familiarity with base bioconductor objects, including the SummarizedExperiment Class
* Familiarity with linear modelling in R; ANOVA, and goodness of fit tests

Useful publications: 

*  Smirnov, P. et al. PharmacoGx: An R package for analysis of large pharmacogenomic datasets. Bioinformatics 32, 1244–1246 (2016).
* Manem, V. SK. et al. Modeling Cellular Response in Large-Scale Radiogenomic Databases to Advance Precision Radiotherapy. Cancer Research (2019) doi:10.1158/0008-5472.CAN-19-0179.
* Mer, A. S. et al. Integrative pharmacogenomics analysis of patient-derived xenografts. Cancer Res canres.0349.2019 (2019) doi:10.1158/0008-5472.CAN-19-0349.



### Workshop Participation

Participants expected to have the following required packages installed on their machines to be able to run the commands along with the instructors.
PharmacoGx,  Xeva, RadioGx, CoreGx and Biobase from Bioconductor
The workshop will be presented as a set of analysis steps to be replicated by the learners, with instructors available to explain the why and how of applying these functions to the given datasets. Learners will write analysis scripts as well as use interactive commands to explore the generated data structures and results. Learners will then brainstorm potential applications of the analysis results in their field as well as comment on use case examples presented by the instructors on research in our lab.

### _R_ / _Bioconductor_ packages used

Bioconductor:
* https://bioconductor.org/packages/release/bioc/html/PharmacoGx.html
* http://bioconductor.org/packages/release/bioc/html/Xeva.html 
* https://bioconductor.org/packages/3.12/bioc/html/RadioGx.html
* https://bioconductor.org/packages/3.12/bioc/html/CoreGx.html

## Time outline

For a 1-hr workshop:

| Activity                                    | Time |
|---------------------------------------------|------|
| Introduction and Experimental Design                     | 5m   |
| Data Structure and Common Functions Between Packages     | 5m |
| Examining and Extracting data of interest                     | 5m |
| Visualizing and modelling Sensitivity Data                     | 14m |
| Summary Functions                     | 3m |
| Signature Generation and Biomarker Discovery                   | 5m |
| Integrative Analysis Across Packages and Disciplines: - 20 Minutes - Interactive Portion | 20m | 


## Workshop goals and objectives

### Learning goals

* Describe pharmacogenomic datasets and radiogenomic datasets and usefulness in cancer research
* Learn how to extract information from these datasets and to intersect them over their common measured features, experiments, model systems 
* Learn how to visualize experimental results from these datasets 
* Learn how to model dose-response for both small compound and radiotherapy datasets
* Learn measures to quantify the response in both cell line and PDX sensitivity screens, for both drug and radiation treatments
* Understand the differences in experimental design between radiotherapy and small compound treatments in cell lines
* Understand the differences in measuring response to therapy between cell line and PDX based models
* Understand how to identify potential genomic signatures of drug and radiation response and explore how synergies between these signatures can inform clinical trial design

### Learning objectives

* List available standardized pharmacogenomic and radiogenomic datasets and download them
* Access the molecular features, dose-response and metadata contained within the data structures defined in the packages
* Create drug-dose and radiation-dose response plots for cell line experiments
* Create tumor growth curve plots for PDX experiments
* Fit linear-quadratic models to radiotherapy experiments in cell lines
* Fit Hill Slope models to dose-response experiments using small compound treatments in cell lines
* Calculate the AAC, AUC, IC50, SF2, D10 metrics for response quantification in cell lines
* Calculate the mRECIST and other tumour growth curve summary metrics
* Visualize response of PDX experiments using an Oncoprint heatmap
* Predict in vivo and in vitro univariate biomarkers using the PharmacoGx, Xeva and RadioGx packages
* Compare signatures of response between chemotherapy compounds and radiotherapy
* Compare univariate biomarkers between cell line and PDX experiments
