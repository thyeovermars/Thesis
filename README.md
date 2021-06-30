# Simulation study that compares imputation procedures in a prediction context
This repository contains all files needed to replicate the simulation study presented in 
_"Simulation study that compares multiple imputation procedures in a prediction context"_. This project served as my MSc thesis, and was completed at the Applied Data Science at Utrecht University, Netherlands.

## Simulation period 
**Author:** Thye Overmars

**Preparation & simulation period:** April 2021 - July 2021

## Abstract
In this simulation study, I first obtained an incomplete dataset from the observed data. The observed data is the Pima Indians Diabetes Dataset (PIDD). Thereafter, the generated imputation data is done by different imputation techniques. The results show that different evaluation techniques show different imputation methods as the best prediction method. Different performance measures yield different conclusions about the imputation methods. The unwary simulator has to look carefully and might be tempted to choose a less good method. A logical starting point is to use a multiple imputation method by default, preferably Bayesian linear regression imputation or stochastic regression imputation. With these two methods you are at least sure of valid estimates, even though they may not be the best predictions.

## Contents
This repository is split into several folders.
1. `Data` contains the Pima Indians Diabetes Dataset (PIDD).
2. `Proposal` contains the propasal of the study. 
3. `Simulation code` contains the script to do the analysis. 

## Software requirements
This simulation study was conducted in R (version 4.0.5) using RStudio (version 1.2.5042). 
Below you can find packages used and the specific versions.

| Package | Version | Description |
|---------|:-------:|:------------|
| `mice`   | 3.13.7   | Performing multiple imputation |
| `ggplot`  | 3.3.3   | Data visualization |
| `tidyverse` | 1.3.0 | Data wrangling |
| `dplyr`   | 1.0.6   | A grammar of data manipulation |
| `jtools`  | 2.1.3   | Analysis and Presentation of Social Scientific Data |
| `tidyr`   | 1.1.3   | Tidy messy data |
| `purrr`   | 0.3.4   | Functional programming tools |
| `readr`   | 1.4.0   | Read rectangular text data | 
| `magrittr` | 2.0.1  | A forward-pipe operator for R | 


## Privacy and ethical considerations
As this is a simulation study in which not only missingness, but also the data were simulated, no privacy issues and ethical considerations had to be dealt with.

## Contact
For questions or suggestions, please contact the person responsible for this archive.

**Name:** Thye Overmars

**Email:** thye.overmars@gmail.com

