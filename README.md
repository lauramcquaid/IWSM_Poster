# Poster for IWSM (International Workshop on Statistical Modelling) 2022 - Trieste, July 18-22, 2022 

This repository contains a poster, which shows my research on the penalized Power-Generalized Weibull (PGW) Multi-Parameter Regression (MPR) model titled "Penalized Power-Generalized Weibull distributional regression". 

This research uses the PGW distribution, which encompasses a number of popular survival distributions and as such has a wide variety of hazard shapes making it a very flexible model. Unlike the proportional hazards (PH) model, which is commonly used in survival analysis, the penalized PGW MPR model allows multiple distributional parameters to depend on covariates. Variable selection and parameter estimation are carried out using penalized regression. The adaptive lasso penalty is used.

This model has been assessed through simulation studies and has been applied to real-world data. The MPR model is compared to the PH model, using the veteran dataset in R, where the MPR model allows for time-varying hazard ratios, which the PH model cannot pick up. This may lead to an increased understanding of real-world data.
