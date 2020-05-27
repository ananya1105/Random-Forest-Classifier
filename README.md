# Random-Forest-Classifier

This is an implementation of Random Forest Classifier. I have taken the reference from this article - https://medium.com/@hjhuney/implementing-a-random-forest-classification-model-in-python-583891c99652
The dataset used in the implementation can be accessed from the data folder inside this repository, alternatively you can also access the data from here- https://www.kaggle.com/uciml/pima-indians-diabetes-database

Shape of the Dataset = (768,9)
All the columns except the target variable are continuous numerical variables
Missing/Duplicate Values - 0
Independent Variables = 'preg', 'plas', 'pres', 'skin', 'test', 'mass', 'pedi', 'age'
Target Variable = 'class' 

Concepts Used:
1. Missing Data Analysis : Missingno library in python
2. Data Normalization: MinMaxScaler: https://towardsdatascience.com/scale-standardize-or-normalize-with-scikit-learn-6ccc7d176a02
3. Data Comparison using subplots: 
4. Random Forest Classifier: Random Forest - https://www.youtube.com/watch?v=J4Wdy0Wc_xQ, Decision Tree/Gini Index - https://www.youtube.com/watch?v=7VeUPuFGJHk, Decision Tree/Feature Selection and Missing Data - https://www.youtube.com/watch?v=wpNl-JwwplA

5. classification_score(evaluation),confusion_magtrix(evaluation): https://drive.google.com/drive/folders/1cstwpF9PAX0eRmCuXA3ffrsq0S3pi4S0
