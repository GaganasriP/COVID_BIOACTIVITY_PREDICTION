# COVID_BIOACTIVITY_PREDICTION

The folder contains two directories (notebook and data), a readme file, and a document.
The notebook directory consists of 2 Jupyter notebooks -

●	DATA _EXTRACTION_CLEANING_PREPROCESSING:
Modules used-

1.	To extract data:
pip install chembl_webresource_client
pandas
 		chembl_webresource_client.new_client-new_client
numpy
2.	To obtain SMILES and descriptor values:
rdkit-Chem
rdkit.Chem -Descriptors

●	MODELLING_DATA:
Modules used-

1.	For training and test sets:
sklearn.model_selection import train_test_split
2.	SVR:
sklearn.svm-SVR
sklearn import linear_model
statsmodels.api 
sklearn.metrics- mean_squared_error, r2_score
3.	Random Forest:
sklearn.ensemble- RandomForestRegressor
4.	Plots
matplotlib.pyplot
pandas.plotting- scatter_matrix


The data directory has the data file with refined descriptors and values created using rdkit module.
Kindly make sure all the modules have been installed in the working environment to run the files.

