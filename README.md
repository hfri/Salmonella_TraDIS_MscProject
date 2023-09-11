# Salmonella_TraDIS_MscProject

In this resporitory, I you can find the datafiles and scripts used for analysing M-SL1344, M-D23580, HeLa cells, and M-RNAseq. The files needed for the analysis and the respective scripts are added to respective folders.
I also added a folder where I added all datasets ultimately used for later integrated analyses, including a script where I compiled them into a large dataframe.

## Source data
Comming soon.. 
- Overview of content of used data and description of what was done to it + respective script
### TraDIS data- this study
- [SL1344 TraDIS data](M_SL1344)
### Public data
TraDIS data(README.md)
- [Public data](README.md)
    - [Canals et al. 2019](M_D23580)
        - Fitness data of str D23580 survival in macrophages, SPI-2 inducing media (InSPI-2) or LB. 
        - Data: read counts for macrophage model and insertion indices for in vitro conditions
        - Re-analysis: complete fitness and pathway analysis
    - [Wang et al. 2016](HeLa) 
        - Fitness data of strain 14280s in HeLa cells (one passage)
        - Data: read counts,logFCs, p-values
        - Re-analysis:fitness analysis and pathway analysis
    - [Chaudhuri et al. 2013](README.md)
        - Fitness data of strain SL1344 in Balb/c mice; food animal data was not utilised due to concerns regarding stochastic loss in the data
        - Data: read counts,logFCs, p-values
        - Re-analysis: taken as logFC corresponding to the minimal adjusted p-val because statistics were provided per insertion site
    - [Grant et al. 2016](README.md)
        - Fitness data of strain SL1344 for gp91 -/- phox mice.
        - Data: read counts,logFCs, p-values
        - Re-analysis: taken as logFC corresponding to the minimal adjusted p-val because statistics were provided per insertion site
    - [Mandal et al. 2016](README.md)
        - Fitness data of strain 14280s grown in different in vitro conditions
        - Data: gene names with fitness effects
        - Re-analysis: None
### Integrative analysis
- folder contains a script that was used to compile and format a lot of the datasets at once
- data folder contains input data, these are datafiles that came from different individual analyses
- formatted_data contains the datafiles that come out of the compilation step using SCRIPT X and were used for subsequent plots etc. 

