An end-to-end Machine Learning pipeline using Logistic Regression and Scikit-Learn to predict passenger transportation on the Spaceship Titanic dataset, featuring automated feature engineering, multi-strategy imputation, and model persistence.

**Preprocessing & Feature Engineering:** Extracts categorical features from complex IDs and cabin assignments, handling missing data using a hybrid strategy of KNN, median, and mode imputation.

**Core Model & Pipeline:** Implements a scikit-learn Logistic Regression classifier with feature scaling and one-hot encoding, persisting fitted transformers via joblib to prevent data leakage.

**Inference & Workflow:** Uses a clean, modular two-script architecture (train.py and test.py) to systematically train, evaluate, and generate Kaggle-ready submission predictions.

# FEBS_TITANIC_PS_GROUP_7
Contributions of members:
Samay-
Data Preprocessing-Worked on writing code for encoding and PCA for given dataset(However PCA was dropped in the final code as it reduced the accuracy of the regression model)
Data Analysis-Wrote the code for the regression model from sklearn
Model Implementation-Implemented the joblib module to call model in test.py 

Kushagra-
Data Preprocessing- Worked on writing code for imputation and scaling of provided dataset
Data Analysis- Tried to find features to be kept in the final processed dataset to get maximum accuracy from model
Model Implementation-Created processing fucntion in test.py and extracted output    
