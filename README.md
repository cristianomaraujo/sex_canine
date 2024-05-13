# Cone Beam Computed Tomography (CBCT) Analysis for Sex Estimation in Human Dentition

## Overview
This repository contains the code and documentation for a study conducted to assess the potential of cone beam computed tomography (CBCT) scans in estimating the sex of individuals based on dental measurements.

## Participants
The study utilized a sample of 662 CBCT scans, with a total of 1093 right and/or left upper canines analyzed.

## Study Variables and Data Collection
Each CBCT scan had the sex of the individual determined (female or male) based on patient-provided information at the time of the scan. Radiant program (Medixant, Poznan, Poland) was used for the analysis by a calibrated examiner. The intraclass correlation coefficient (ICC) was calculated to assess the reproducibility of measurements. 

Navigation lines were positioned along the long dental axis and perpendicular to it in the three tomographic sections. Measurements were recorded in millimeters (mm) for linear measurements.

## Data Analysis and Model Construction
To identify variables with greater predictive capability, a univariate analysis was performed using statistical tests. A bivariate analysis was conducted to evaluate correlation between independent variables. Imbalanced classes were addressed using the Edited Nearest Neighbours (ENN) method.

Predictive classification models were constructed using machine learning algorithms including Gradient Boosting Classifier (GBC), Logistic Regression (LR), Support Vector Machine (SVM), Random Forest Classifier (RFC), Multilayer Perceptron Classifier (MLPC), K-Nearest Neighbors (KNN), and Decision Tree Classifier (DTC). Grid Search method was applied to optimize model performance.

## Training, Cross-Validation, and Test
80% of the data were used for training and cross-validation, with the remaining 20% for testing. Cross-validation was conducted using the k-fold cross-validation technique. Model performance was evaluated based on areas under the curve (AUC), ROC curves, and various metrics including accuracy, recall, precision, and F1 Score.

## Availability
The Python programming code used for this study is openly accessible in this repository.

For more detailed information, refer to the study documentation and code provided in this repository.
