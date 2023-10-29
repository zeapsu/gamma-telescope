# MAGIC Gamma telescope

Application using the [MAGIC Gamma telescope](https://archive.ics.uci.edu/dataset/159/magic+gamma+telescope)
dataset from UCI

Primary purpose is to use this dataset to implement and get comfortable with
multiple training strategies used to train models

## Commands used

For making a file with all the installed module dependencies

`pip freeze > requirements.txt`

For installing dependencies

`pip install -r requirements.txt`

For jupyter notebook seeing the venv and the modules we set the venv kernel

`python -m ipykernel install --user --name=[name of your environment]`

## Steps taken

1. Got data set, set up python venv, set up project tree
2. Prepping to visualize data on Jupyter notebook
3. Data visualization, but with unprepared data
4. Segment data -> created training, validation, and testing set
5. Clean data and prep for binary classification

## TODO:

- Implement the following Algorithms with Scikit-learn, Keras, and, Tensorflow, then manual implementation using
  vanilla python

  - Supervised Learning

        - K-Nearest Neighbors (KNN)
        - Naive Bayes
        - Logistic Regression
        - Linear Regression
        - Linear Regression using a Neuron
        - Support Vector Machine (SVM)
        - Classification Neural Net(NN) using Tensorflow
        - Pay attention to Binary Cross-Entropy Loss
        - Regression NN using Tensorflow

  - Unsupervised Learning

        - K-Means Clustering
        - Principal Component Analysis (PCA)

- Brush up/learn the statistics (distributions) required for manual implementation (focus on
  manual implementation last)

- Aim to get a good understanding of loss functions [L1 (MAE), L2 (MSE),
  Cross-Entropy Loss, SVM Loss]
