# Overview of reproducible data processing
## Characterisation of viromes in farmed Atlantic salmon (*Salmo salar*) and exploration of viral relations to the bacterial community and fish disease state
This repository contains the data and R scripts used for the analyses on 40 farmed Atlantic salmon viromes for the MSc thesis work by Caroline Sophie Wolters Petersen at the University of Copenhagen.

In the data folder all the data used in the three different scripts are found, including data used from Bozzi et al (https://github.com/DavideBozzi/Bozzi_et_al_2020_analysis), that have been slightly modified to only encompass the overlapping samples. 

There are three R scripts: 
1. QC of data - to estimate sequencing efforts using statistics and a general overview of the data generated
2. Decontamination of data - removal of contaminants using the R package Decontam
3. Final analyses including alpha and beta diversity, differential abundance, and correlation analyses.
