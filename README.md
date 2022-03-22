# DeepQuantileRegressionOPF

This repo collects the samples used in paper "Deep-quantile-regression-based surrogate model for joint chance-constrained optimal power flow with renewable generation".


## File descriptions
__DeepQuantileRegression.7z:__ 
This 7z file contains all samples we used in our paper. This 7z file contains the following three folders:

    Gaussian: the samples used in Case 1 with Gaussian distributed uncertainties
    Beta: the samples used in Case 2 with Beta distributed uncertainties
    Weibull: the samples used in Case 3 with Weibull distributed uncertainties

In each folder, there are six .csv files:

    x_monial.csv: the nomial nodal power injections
    x_actual.csv: the actual nodal power injections
    omega.csv: samples of uncertainties from distributed renewable generation
    h.csv: maximum violation of power flow constraints
    x_DataAugmentation.csv: samples of nodal power injections after data augmentation step
    h_DataAugmentation.csv: samples of the maximum constraint violation after data augmentation step
    