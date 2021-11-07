# Project Description

This is the repository for the PSYC575 Class Project dealing with the effect of birth experience and delivery method on parental stress. We use time series data of over 100 couples with at least at least 3 measures in 3, and 6 month intervals. The data is nested in participants (mother/father) which are again nested in couples, resulting in a three level hierarchichal data structure.

We use a multi-level model using the lme4 package in r to model parental stress over birth experience and birth delivery method and account for N covariates (X, Y, Z).

IMAGE OF DATA STRUCTURE

We find that ...

# Data Used

The data from the Hormones Across the Transition to Childrearing (HATCH) study was used in this project. The HATCH study was conducted by Dr. Darby Saxbe and the NEST Lab at the University of Southern California. Because of the sensitivity of the data, the data set cannot be shared without IRB and PI approval. Please contact Elizabeth Aviv (eaviv@usc.edu) with questions. 


# Instructions

To replicate the results, use the `final-project-analyses.Rmd` file. All analysis, data transformations and modelling are included. If you use different data with different variables for analogeous analyses, the respective names need to be adjusted in the code.