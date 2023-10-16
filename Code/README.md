# Code

This section of the GitHub Repository stores code designed, implemented and tested in the duration of this project. The code is split into two facets: (1) Dataset Aquisition, Processing & Curation and (2) Machin Learning (ML) models

## Dataset Aquisition, Processing & Curation
The datasets were prepared for ML input and are the combination of flux tower ground truth data and satellite imagery data. The detailed description of these datasets and their formation can be found in the Project Report. There are 3 Jupyter Notebooks that were used to implement this aspect of the project: (1) Flux Tower Data Processing, (2) Landsat Satellite Data Processing and (3) Data Aquisition, Processing and Collation. The first two were used to aquire and process the two necessary datasets separately to ensure proper code execution and no error and the last is the combination and final dataset preparation. 

Note: these Jupyter Notebooks were run in Google Colab and mounted to Google Drive. Therefore the file paths are specific to this project's application and will cause code error and inaction if implemened as is - the file paths will need to be altered as detailed in the User Manual.

## Machine Learning Models
The five ML models used in this project, namely: Neural Network (NN), (2) Recurrant Neural Network (RNN), (3) Long Short-Term Memory (LSTM), (4) Random Forest (RF) and (5) State Vectore Machine (SVM) were also implemented in Google Colab Jupyter Notebooks. These Notebooks are available here and will also require small alteration for code execution (i.e. change of file path for ML dataset).
