# self-social-sharing
This repository contains code for the analyses reported in the following manuscript:

**Message self and social relevance is positively related to sharing intentions: Correlational and causal evidence from six studies**


## Compiled analysis files

Demographic information is reported [here](https://cnlab.github.io/self_social_sharing/analysis/demographics)

The correlational analyses are reported [here](https://cnlab.github.io/self_social_sharing/analysis/correlational)

The causal analyses are reported [here](https://cnlab.github.io/self_social_sharing/analysis/correlational)

The specification curve analyses are reported [here](https://cnlab.github.io/self_social_sharing/analysis/sca)

The downsampled analyses are reported [here](https://cnlab.github.io/self_social_sharing/analysis/downsampled_analysis)


## Directory structure

* analysis = R code for the analyses reported in the manuscript and supplementary material
* cleaning = R code and supporting files for cleaning the data

````
├── analysis
│	├── causal.Rmd
│	├── causal.html
│	├── correlational.Rmd
│	├── correlational.html
│	├── demographics.Rmd
│	├── demographics.html
│	├── downsampled_analysis.Rmd
│	├── downsampled_analysis.html
│	├── indirectMLM.R
│	├── models
│	│	├── model_mediation_self_broadcast.RDS
│	│	├── model_mediation_selfnarrowcast.RDS
│	│	├── model_mediation_social_broadcast.RDS
│	│	├── model_mediation_social_narrowcast.RDS
│	│	├── sca_output_12.RDS
│	│	├── sca_output_3a.RDS
│	│	└── sca_output_3b.RDS
│	├── sca.Rmd
│	├── sca.html
│	├── study1_prep.Rmd
│	├── study2_prep.Rmd
│	├── study3_prep.Rmd
│	├── study4_prep.Rmd
│	├── study5_prep.Rmd
│	└── study6_prep.Rmd
└── cleaning
	├── cleaning_script_study1a.Rmd
	├── cleaning_script_study1b.Rmd
	├── cleaning_script_study1c.Rmd
	├── cleaning_script_study1d.Rmd
	├── cleaning_script_study2.Rmd
	├── cleaning_script_study3.Rmd
	├── cleaning_script_study4.Rmd
	├── cleaning_script_study5.Rmd
	├── cleaning_script_study6.Rmd
	└── state_codes.csv
```