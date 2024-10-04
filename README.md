## Breast Cancer Classification Using ID3 Decision Tree Algorithm:

Assignment Description:

The assignment focuses on the implementation of the ID3 Decision Tree algorithm, an essential machine learning technique for classification problems. The project uses a dataset related to breast cancer, where attributes like mean radius, perimeter, and smoothness are used to classify whether a tumor is malignant or benign. The decision tree is constructed using the ID3 algorithm, which relies on entropy and information gain to make predictions by learning decision rules.

Purpose of the Project:

The purpose of this project is to implement the ID3 decision tree algorithm and apply it to a real-world classification problem using breast cancer data. The goal is to build a predictive model that can accurately classify tumors as malignant or benign based on the dataset's features. This project also serves to evaluate how well the ID3 algorithm performs on medical data, exploring its advantages and limitations in practical applications.

Objectives:

1. Implement the ID3 algorithm to build a decision tree.
2. Calculate entropy and information gain to determine the best attribute splits.
3. Train the decision tree model using a classification dataset on breast cancer.
4. Evaluate the model's performance using the test set.
5. Identify which attributes are most significant in predicting whether a tumor is malignant or benign.
6. Visualize and analyze the decision tree, considering factors such as tree depth and pruning.
7. Conclude with the strengths and weaknesses of decision tree algorithms, especially when used in medical diagnoses.

Technologies Used:

Python: For data processing, modeling, and analysis.
Jupyter Notebook: As the primary environment for running Python scripts and generating insights.

How to run the code:

1. Clone the GitHub repository.
2. Navigate to the project directory.
3. Install the required dependencies.
4. Open the Jupyter notebook.
5. Run the script below to load the dataset.

   import pandas as pd
   
   import numpy as np
   
   import matplotlib.pyplot as plt
   
   from sklearn.datasets import load_breast_cancer
   

   OR view the code/results via the google colab link  
https://colab.research.google.com/drive/1jC9zWP-wBXuYrG6lD92ha3SaP6Tz1eoY?usp=sharing#scrollTo=CCkHP_k6ZHlF
