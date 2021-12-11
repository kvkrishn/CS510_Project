# CS510_Project
Github Repository for CS 510 Project: Analysis of Different Predictive Models for the Prediction of Aromatic Rings of Cancer SRC Kinase Inhibitors
Author: Keerthi Krishnan

Premise: SRC Kinase Inhibitors are important protein inhibitors and potential drug candidates for cancer proteins. They play an important role in suppressing tumor growth and oncogenesis in tumor proteins. A distinction factor of SRC Kinase Inhibitors and their existence is their ring count and it acts as a very important feature for these molecules. Potentially, the ring count can affect binding modes of these inhibitors to different cancer proteins. Therefore, I plan on predicting aromatic ring count given a list of 20 aggregate chemical features and using different machine learning models for comparison analysis. I compare 4 models: Linear Regression, Log-Linear Regression, Random Forest, and Neural Network Model to see which out of the 4 do the best in prediction of number of aromatic rings in the dataset. The main goal is to identify the best model to predicting the number of rings in kinase inhibitors.  

Data: SRC Kinase inhibitor Dataset(xlsx file) contained in data file 
	Contains multiple(~20) chemical features that describe the molecule
  Prediction variable: Rings

Details: Data contains ~3000 molecules with smile strings and ~20 aggregate chemical features

Output: Initial visualization of data and correlation plots. 
        Summary statistics and accuracy measures of different models: Linear Regression, Log-Linear           Regression, RF, and Neural Network model on training and testing(plots, variance level, rmse,         degrees of freedom, etc)

All code is contained in the R notebook and if run, should contain comments and information on how to load dataset and what each step is doing and functioning. Make sure the dataset is in the same directory as the R notebook for the code to load dataset properly. 
