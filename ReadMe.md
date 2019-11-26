# Background

This repo was created during the second project of my Udacity Machine Learning Nanodegree. This project required a fraud detector model to be built.
I chose to build a custom PyTorch Neural Network to classify an answer text as either fraudulent or not based on its similarity to a source text file.

# Included
 - source_pytorch folder: This folder includes the following files, which are required for the constructing, training and testing of the custom PyTorch model:
  - train.py: Contains the training code
  - predict.py: Contains the code to test the model
  - model.py: Contains model details and hyperparameters
 - 2_Plagiarism_Feature_Engineering.ipynb: This Jupyter Notebook contains all the code required to engineer the features which will be fed to the model, e.g. containment values and longest common subsequence values
 - 3_Training_A_Model.ipynb: Jupyter Notebook in which the model is trained, deployed and tested. Makes use of the files train.py and predict.py.
 - helpers.py: Python file containing additional functions required during the feature engineering stage of the project.
 - problem_unittests.py: Python file that runs unit tests for the functions in the 2_Plagiarism_Feature_Engineering.ipynb to ensure our code is working properly
 
