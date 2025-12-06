Parkinson's Disease Prediction using SVM

This project implements a machine learning model to predict Parkinson’s Disease using biomedical voice measurements. The aim is to show how vocal biomarkers combined with Support Vector Machines (SVM) can help in early and reliable detection.

Dataset

The dataset contains several vocal features, including:

Fundamental frequency (MDVP:Fo)

Jitter and shimmer values

Harmonic-to-noise ratios

Other biomedical voice parameters

Each row includes a status label, where 1 indicates Parkinson’s and 0 indicates healthy.

The dataset is taken from the UCI Machine Learning Repository.

Project Workflow

Data loading

Exploratory data analysis

Cleaning and handling non-numeric fields

Feature scaling

Train–test split

Model training using SVM

Model evaluation using accuracy, precision, recall, and a confusion matrix

Model

The Support Vector Machine classifier is used because it handles high-dimensional data effectively and provides clear decision boundaries for classification tasks.
