Classifying Handwritten Digits (Modified MNIST, two digits in one sample)

Dataset used: https://drive.google.com/file/d/1yqAvZ-MymLDIKns_XbfcTGgxAmC_kHJu/view?usp=sharing

For reproducibility, the models can be run on either Kaggle notebook, google colab or any notebook that allow some degree of GPU usage to avoid long training time.

The notebook CNN-HP contains the CNN model. It requires GPUs (the one I used was GPU T4 x2 provided by Kaggle) to be able to complete process within 1 hour and half, since it has hyperparameter tunning.

The notebook LOGREG contains the logistic regression model from scratch. It may take around 2 hours since it's built from scratch thus less efficient compared to algo using libraries.

The notebooks NN and RANDOMFOREST contain respectively NN model and random forests model. They should finish within 15 mins each.