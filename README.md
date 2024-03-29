# BELAs_Schumacher_et_al

This repository contains all code used for the analysis in:

>**Tissue-intrinsic beta-catenin signals antagonize Nodal-driven AVE differentiation**  
>Sina Schumacher, Max Fernkorn, Michelle Marten, Rui Chen, Yung Su Kim, Ivan Bedzhov, and Christian Schröter  
>*[Insert Link/Publication details here]*

Analysis of imaging data to quantify polarization of BELAs in:
Polarization_analysis.R

Analysis of single cell RNA sequencing data:
This includes the normalization, clustering, the identification of differentially expressed genes and cell-cell-communication analysis based on the dataset of BELAs, Epi cysts and VE cysts as well as the integration with the public embryo datasets.
The single cell sequencing data from the in vitro system described in this study can be found under [GSE198780](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE198780).

The analysis of only the in vitro dataset as well as all visualizations were performed in R, the integration and label transfer based on public embryo datasets in python. The structure of the analysis and which files contain which anlysis steps is described here:

![Overview_Analysis_Workflow_1](https://user-images.githubusercontent.com/88881773/235701686-8cbd2a76-610b-4f6f-88e3-4aa3872fc047.png)
