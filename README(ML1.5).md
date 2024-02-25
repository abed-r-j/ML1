##### Abed El Rahmane Jaafir (Email: abedelrahmane.jaafir@net.usj.edu.lb, Matricule: 210950)
##### Nicola Lawandos (Email: nicola.lawandos@net.usj.edu.lb, Matricule: 201161)
# Deep Learning Classification On A Numeric Dataset

Probability of some patients having a heart attack.


## Description

Utilizing a TensorFlow model and exploring data through visualizations before building and evaluating the model.


## Key Highlights

1. Preprocessing the data by handling missing values, duplicates, and scaling numerical features.
2. Performing exploratory data analysis (EDA)..
3. Building a TensorFlow model with two hidden layers and evaluating its performance using binary cross-entropy loss and accuracy metrics.
4. Visualizing the model's expectations and comparing them to the actual labels.


## Table of Contents

1. Loading Packages and Data
2. Dataset Overview
3. Exploratory Data Analysis (EDA)
4. Model Training
5. Evaluation


## 1. Loading Packages and Data

1. Pandas
2. NumPy
3. Matplotlib
4. Seaborn
5. TensorFlow


## 2. Dataset Overview

The dataset (`ML1.5.csv`) contains information about patients. The data is split into training and test sets, and any duplicates are addressed during the preprocessing stage.


## 3. Exploratory Data Analysis (EDA)

EDA involves visualizing relationships between variables using pair plots and heatmaps to understand correlations. Duplicate rows are identified and addressed.


## 4. Model Training

A deep learning model is constructed using TensorFlow and Keras. The architecture includes a hidden layer with ReLU activation and an output layer with a sigmoid activation function. The model is compiled using binary cross-entropy loss and ..


## 5. Evaluation

The trained model is evaluated on the test set, and metrics such as binary accuracy and overall accuracy are reported.
