# self-social-sharing
This repository contains code for the analyses reported in the following manuscript:

[**Cosme et al. (Preprint) Message self and social relevance increases intentions to share content: Correlational and causal evidence from six studies**](https://psyarxiv.com/9cxfj/)


## Compiled analysis files

Demographic information is reported [here](https://cnlab.github.io/self-social-sharing/analysis/demographics)

The correlational analyses are reported [here](https://cnlab.github.io/self-social-sharing/analysis/correlational)

The causal analyses are reported [here](https://cnlab.github.io/self-social-sharing/analysis/causal)

The specification curve analyses are reported [here](https://cnlab.github.io/self-social-sharing/analysis/sca)

The downsampled analyses are reported [here](https://cnlab.github.io/self-social-sharing/analysis/downsampled_analysis)

## Analysis reproduction
To reproduce the analyses in the manuscript, first execute the study cleaning scripts, then the study prep scripts, and finally the analysis scripts (`demographics.Rmd`, `correlational.Rmd`, `causal.Rmd`, `sca.Rmd`, `downsampled_analysis.Rmd`). 

Individual demographic data is not shared publicly due to concerns related to potential identifiability of participants, but is available upon request. Therefore, the analyses in `demographics.Rmd` and `sca.Rmd` are not fully reproducible because these data are required to run the some or all of the code. The specification curve analysis can be reproduced without these data by loading the models saved in `sca_output.RDS` and executing the code from line 305 and onward. If you would like to request these data, please email Dani Cosme at danielle.cosme@asc.upenn.edu

## Directory structure

* `analysis` = R code for the analyses reported in the manuscript and supplementary material
* `cleaning` = R code and supporting files for cleaning the data
* `data` = text files containing the data
* `stimuli` = text files containing the newspaper article stimuli from Studies 4-6; stimuli from Studies 1-3 are available on [OSF](https://osf.io/nfr7h/)

````
├── analysis
│   ├── causal.Rmd
│   ├── causal.html
│   ├── correlational.Rmd
│   ├── correlational.html
│   ├── demographics.Rmd
│   ├── demographics.html
│   ├── downsampled_analysis.Rmd
│   ├── downsampled_analysis.html
│   ├── indirectMLM.R
│   ├── models
│   │   ├── model_mediation_self_broadcast.RDS
│   │   ├── model_mediation_selfnarrowcast.RDS
│   │   ├── model_mediation_social_broadcast.RDS
│   │   ├── model_mediation_social_narrowcast.RDS
│   │   └── sca_output.RDS
│   ├── sca.Rmd
│   ├── sca.html
│   ├── study1_prep.Rmd
│   ├── study2_prep.Rmd
│   ├── study3_prep.Rmd
│   ├── study4_prep.Rmd
│   ├── study5_prep.Rmd
│   └── study6_prep.Rmd
├── cleaning
│   ├── cleaning_script_study1a.Rmd
│   ├── cleaning_script_study1b.Rmd
│   ├── cleaning_script_study1c.Rmd
│   ├── cleaning_script_study1d.Rmd
│   ├── cleaning_script_study2.Rmd
│   ├── cleaning_script_study3.Rmd
│   ├── cleaning_script_study4.Rmd
│   ├── cleaning_script_study5.Rmd
│   ├── cleaning_script_study6.Rmd
│   └── state_codes.csv
├── data
│   ├── study1.csv
│   ├── study1a_clean_long.csv
│   ├── study1b_clean_long.csv
│   ├── study1c_clean_long.csv
│   ├── study1d_clean_long.csv
│   ├── study2.csv
│   ├── study2_clean_long.csv
│   ├── study3.csv
│   ├── study3_clean_long.csv
│   ├── study4.csv
│   ├── study4_clean_long.csv
│   ├── study5.csv
│   ├── study5_clean_long.csv
│   ├── study6.csv
│   └── study6_clean_long.csv
└── stimuli
    ├── study4_articles.csv
    ├── study5_articles.csv
    └── study6_articles.csv
```
