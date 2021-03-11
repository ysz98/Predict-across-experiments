# Predict-across-experiments
Example code and data for predict hybrid performance across experiments. 
The GBLUP model uses BGLR package (Pérez and de los Campos, 2014) in R (R Core Team, 2019). The R version used in this work is <= 3.6.0. 
The example codes used Exp. II as the training set and Exp. III as the test set. 
The input data includes three files. 
The file "Integrated data BLUEs of the hybrid trials.txt" is the integrated phenotypic data with 11 columns, while the first four columns are the BLUEs for grain yield (Mg ha -1), parental information, genotype name, and the rest column are the design matrix for hybrid, lines and experiments, respectively. 
The file "Integrated data SNP of the hybrid trials.zip" is integrated SNP data of all lines and hybrids used for Experiment I-V. 
