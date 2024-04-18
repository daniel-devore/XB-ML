# Data_and_Molecular_Fingerprint_Driven_Machine_Learning_Approaches_to_Halogen_Bonds

The following depository contains the code, figures, and data for the article 
produced by Daniel P. Devore and Kevin L. Shuford, "Data and Molecular Fingerprint Driven Machine Learning 
Approaches to Halogen Bonding" {Enter Journal Name Here} 
DOI: {Enter DOI Here}.

The python code for the machine learning approach for predicting the magnitude of the $\sigma$-hole (V$_{S,Max}$), 
binding energy (E$_{bind}$), and the X$\cdots$N local force constant (k$^{a}_{X\cdots N}$) 
by the molecular fingerprints and previously obtained data from the published articles by Daniel P. Devore, 
Thomas L. Ellington, and Kevin L. Shuford (DOI: 10.1021/acs.jpca.3c06894 and DOI_HERE)
is provided in the jupyter notebook.

The Data folder contains the Data implemented into the machine learning algorithms. The Feature_columns 
directory contains the names of the Features (properties) that was used to predict the three above mentioned 
properties in the data driven approach. The CV_results directory contains the coefficient of determination (R$^2$), 
mean absolute error (MAE), and root mean squared error (RMSE) data for all 5-fold cross validation approaches for 
each algorithm. The Figures folder contains all the figures made throughout the provided script.
