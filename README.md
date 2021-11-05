# CS510_Project
Github Repository for CS 510 Project: Prediction of Aromatic Rings for Cancer Kinase Inhibitors Using Random Forest Model

Premise: SRC Kinase Inhibitors are important protein inhibitors for cancer proteins. They play an important role in suppressing tumor growth and oncogenesis in tumor proteins. A distincting factor of SRC Kinase Inhibitors and their existence is their ring count
and it acts as a very important feature for these molecules. In this project, I plan on predicting aromatic ring count given a list of 20 aggregate chemical features 
and using different machine learning models for comparison analysis. I compare 4models: Linear Regression, Log-Linear Regression, Random Forest, and Neural Network Model to see which out of the 4 do the best in prediction of number of aromatic rings in the dataset. The main goal is to identify the best model to predicting the number of rings in kinase inhibitors.  

Data: SRC Kinase inhibitor Dataset(xlsx file)
	Contains multiple chemical features, that describe the molecule

Output: Summary statistics of Linear Regression, Log-Linear Regression, RF, and Neural Network model on training and testing(plots, variance level, rmse, degrees of freedom, etc)
Details: Data contains ~3000 molecules with smile strings and ~20 aggregate chemical features

All code is contained in the R notebook and if run, should contain comments and information on how to load dataset and what each step is doing and functioning. Make sure the dataset is in the same directory as the R notebook for the code to load dataset properly. 
