# Data

This section of the GitHub Repository stores some of the data used in the porject's application. 

## What is not included?
It does not include the individual AmeriFlux flux tower datasets (which were downloaded from their website) or the individual Landsat satellite datasets (which are generated during the Dataset Aquisition, Processing & Curation process and correspond to the AmeriFlux datasets). It also does not include the merged datasets (which is the combination of the individual AmeriFlux flux tower datasets and the individual Landsat satellite datasets).

This data omission is due to the large number of datasets in each of these three categories: (1) AmeriFlux flux tower datasets, (2) Landsat satellite datastes and (3) merged datasets. 

In the case of the smaller number of dataset when a spatial limitation is applied (i.e. filter of 5 US provincial states) there are 66 (in total: 66 x 3 = 198) and in the case of the larger number of datasets (when that limitation is lifter), there are 375 (in total: 375 x 3 = 1125). 

Because these datasets can be downloaded from the AmeriFlux portal, generated and merged using the code layed out in the Jupyter Notebooks it seem redundant to include. 

## What is included?
However, the following were deemed appropriate for inclusion:

- the AmeriFlux Site Overview datasets for both the smaller and larger (i.e. extended) number of datasets as well as the pre- and post-filtered versions.
- the finalised Machine Learning (ML) datasets which will be inputted into the ML models for both the smaller and larger (i.e. extended) number of datasets as well as with and without the data variable included.
- the Date Variation datasets which are only applied to the smaller dataset size with date included. This contains three versions of said database for ML model perfromance comparison: (1) date variable is a String, (2) date variable is converted into Epoch and (3) date variable is converted into Epoch and the day, month and year are extracted as individual variables. 


