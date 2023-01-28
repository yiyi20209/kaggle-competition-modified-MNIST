Classifying Handwritten Digits (Modified MNIST, two digits in one sample)

For reproducibility, please make sure to run these notebooks in default kaggle notebook environnment of the competition (From competition web page: Code -> New Notebook).

The notebook CNN-HP contains the CNN model. It requires Kaggle accelerator GPU (the one I used was GPU T4 x2) to be able to complete process within 1 hour and half, since it has hyperparameter tunning.

The notebook LOGREG contains the logistic regression model from scratch. It may take around 2 hours since it's built from scratch thus less efficient compared to algo using libraries.

The notebooks NN and RANDOMFOREST contain respectively NN model and random forests model. They should finish within 15 mins each.