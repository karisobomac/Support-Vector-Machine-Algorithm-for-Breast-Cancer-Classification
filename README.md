STEP #1: PROBLEM STATEMENT
Predicting if the cancer diagnosis is benign or malignant based on several observations/features

30 features are used, examples:

  - radius (mean of distances from center to points on the perimeter)
  - texture (standard deviation of gray-scale values)
  - perimeter
  - area
  - smoothness (local variation in radius lengths)
  - compactness (perimeter^2 / area - 1.0)
  - concavity (severity of concave portions of the contour)
  - concave points (number of concave portions of the contour)
  - symmetry 
  - fractal dimension ("coastline approximation" - 1)

Datasets are linearly separable using all 30 input features
Number of Instances: 569
Class Distribution: 212 Malignant, 357 Benign
Target class:

   - Malignant
   - Benign
https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)

STEP #2: IMPORTING DATA
#import libraries import pandas as pd # Import Pandas for data manipulation using dataframes import numpy as np # Import Numpy for data statistical analysis import matplotlib.pyplot as plt # Import matplotlib for data visualisation import seaborn as sns # Statistical data visualization #%matplotlib inline #Import Cancer data drom the Sklearn library from sklearn.datasets import load_breast_cancer cancer = load_breast_cancer()

STEP #3: VISUALIZING THE DATA
github-small github-small github-small github-small

STEP #4: MODEL TRAINING (FINDING A PROBLEM SOLUTION)
github-small
