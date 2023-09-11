# Salmonella_TraDIS_MscProject

In this resporitory,  you can find the datafiles and scripts used for analysing M-SL1344, M-D23580, HeLa cells, and M-RNAseq. The files needed for each analysis and the scripts are added to respective folders.
For the integrative analysis, one folder is added with all datafiles ultimately used for later integrated analyses and a script on how datafiles were formatted and compiled.

### TraDIS data- this study
- [SL1344 TraDIS data](M_SL1344)
- Contains scripts and data for differential fitness analysis of M-SL1344
### Public data
TraDIS data
    - M-D23580: [Canals et al. 2019](M_D23580)
        - Contains scripts and data for differential fitness analysis of str D23580 survival in macrophages
        - Re-analysis: complete fitness and pathway analysis
    - HeLa: [Wang et al. 2021](HeLa) 
        - Contains scripts and data for differential fitness analysis of strain 14280s in HeLa cells (one passage)
        - Re-analysis:fitness analysis and pathway analysis
Expression data:
    - M-RNAseq: [Canals et al. 2019b](M-RNAseq)
        -    Contains scripts and data for differential expression analysis of str ST74 survival in macrophages
### Integrative analysis
- folder contains a script that was used to compile and format a lot of the datasets at once
- data folder contains input data, these are datafiles that came from different individual analyses
- formatted_data contains the datafiles that come out of the compilation step using SCRIPT X and were used for subsequent plots etc.
- Data includes result from re-analyses (see above) and:
  - Balb/c: [Chaudhuri et al. 2013]
      - Contains fitness data of strain SL1344 in Balb/c mice; food animal data was not utilised due to concerns regarding stochastic loss in the data
      - Data: read counts,logFCs, p-values
      - Re-analysis: taken as logFC corresponding to the minimal adjusted p-val because statistics were provided per insertion site
  - Immunodeficient mice: [Grant et al. 2016]
      - Fitness data of strain SL1344 for gp91 -/- phox mice.
      - Data: read counts,logFCs, p-values
      - Re-analysis: taken as logFC corresponding to the minimal adjusted p-val because statistics were provided per insertion site
  - In vitro: [Mandal et al. 2016]
      - Fitness data of strain 14280s grown in different in vitro conditions
      - Data: gene names with fitness effects
      - Re-analysis: None

