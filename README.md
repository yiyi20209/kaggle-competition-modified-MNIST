# Overview
Handwritten digits recognition has been a classic supervised Machine Learning (ML) classification problem,
in which MNIST stands as the most popular dataset. In this project, the goal is to design machine learning
models that detect handwritten digits in images containning 2 digits per image (generated from MNIST
dataset) and classify each image as the sum of its 2 digits (e. g. a image of digits “7 5” will be classified as
12). Four models were built in order to reach the goal and compared for analysis:
- Logistic Regression (LogReg) model built from scratch reached an accuracy of 0.214.
- Random Forests (RF) model built using Scikit-Learn (Sklearn) library, reached an accuracy of
0.7496.
- Neural Network (NN) model built using Tesorflow.Keras library, reached an accuracy of 0.9138.
- Convolutionnal Neural Network (CNN) model built using Tesorflow.Keras library and tunned with
Bayesian Optimization search, reached an accuracy of 0.9964.

# contents
- Readme.md                   // help
- classification-of-mnist-digits  // dataset from the kaggle <--need additional download
- data_visualization.ipynb    
- Logreg.ipynb                // logistic regression
    - logreg0.1.json             // weight and bias for logreg
    - logreg0.01.json            // weight and bias for logreg
    - logreg3.json               // weight and bias for logreg
- TreeForest.ipynb            // decision tree; random forest
    - dtree.pickle               // model for decision tree
- SVM.ipynb                   // Support Vector Machines
    - SVM.pickle                 // model for SVM
- ANN.ipynb                   // ANN
    - ANN.h5                     // model for ANN
- CNN.ipynb                   // CNN
    - CNN.h5                     // model for CNN

# How to run
step1:
Download the dataset from the kaggle website and put the folder in the correct location as shown in the directory
    Classifying Handwritten Digits (Modified MNIST):
    https://www.kaggle.com/t/0d0b1c033ece47ffa1dbc8bd374689ae/data

step2:
Configure the right environment, for example: Colab or JupyterNotebook

step3:
To reproduce the project, run the following notebooks in the given order and follow the annotations:
- `LOGREG.ipynb`
- `RANDOMFOREST.ipynb` 
- `NN.ipynb` 
- `CNN-HP.ipynb` 

P.S. The notebook CNN-HP contains the CNN model. It requires GPUs (the one I used was GPU T4 x2 provided by Kaggle) to be able to complete process within 1 hour and half, since it has hyperparameter tunning.