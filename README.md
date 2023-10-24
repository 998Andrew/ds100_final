# Data 100 Final Project: Machine Learning Prediction Model of Contraceptive Mehtod Choice 

Andrew Liu, Terrance Wang

UC Berkeley

The aim of this project is to develop and validate machine learning models using family socioeconomic factorsto best  contraceptive method choice. By better understanding contraceptive method choice, government policy makers can focus policy solutions directed at addressing the determinants that play the largest factor in contraceptive solutions in order to prevent unwanted pregnancies and improve maternal and child health.

## Description of Files
Data100_Final_Project_Report.pdf: final report writeup
Data100_Project.ipynb: jupyter notebook of code, including EDA, visualizations, developing, and validation of model

## Description of Data Source
contraceptive_for_students.csv: A pre-cleaned dataset from the 1987 National Indonesia Contraceptive Prevalence Survey.

## Methodology
data visualization (pandas)
75/25 train-test split used to train logistic regression, SVM with multiple kernels, random forest (sklearn package)

## Results
58.8% test accuracy for the SVM + rbf kernel, 57.2% test accuracy on the SVM + 2 degree polynomial kernel, 56.3% test accuracy on the SVM + linear kernel, 55% on random forest and 57.4% test accuracy on the logistic regression model.

