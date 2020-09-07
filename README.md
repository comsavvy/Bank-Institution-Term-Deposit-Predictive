# Bank-Institution-Term-Deposit-Predictive
##                                             Project objective
## Preprocessing
Encode categorical variables - identify all categorical columns and use one-hot encoding to transform them into numerical columns.  
Handle outliers. 
Use your preferred scaler to rescale all numerical columns. You can read about using MInMaxScaler(), StandardScaler(). The main idea why this is done is that some variables are often measured at different scales and would not contribute equally to model fitting and this may lead the trained model to create some bias. Hence, in dealing with it is usually important to normalize.
Transform and Aggregate columns to create better features
Explore TSNE, autoencoders, and PCA dimensionality reductions techniques.

The objective of this challenge is to build a predictive model if a new bank client would subscribe to a term deposit or not. The following steps would be helpful to carry this task out but you are allowed to use your approach.
### Task 2.2 - Train, Test Split
Split the data using 90% for training and 10% for testing
### Task 2.3 - Select Machine Learning Models
Use cross validation to select the best three machine learning models for submission. 
Use the following cross validation techniques and comment on their differences as well as pros and cons. 
Stratified K-fold
K-fold

Suggested model to explore - you must try the ones in bold:
Logistic regression model
XGBoost
Multilayer perceptron
SVM (rbf, poly, linear)
Decision Trees &  Randomforest


Suggested evaluation metrics to use:
ROC
F1 Score
Accuracy, Precision, Recall 

# Comment on 
Why do you use k-fold training technique? Does Stratified K-fold improve your model? Why or why not?
Why do certain models perform better than others for the data we have?
Which evaluation metric is more appropriate for this project, and why?

### Task 3 - A detailed and well written report
Write a Medium article summarizing the pre processing carried out on the data, the idea behind choosing the type of k-fold, model algorithm,  and evaluation metric. Present a justification for choosing the three models. Your article should have a link to your code in github. Your code in Github should at least have three model functions (if you prefer, you can make module folders instead) and a README and requirements.txt files. 

# The main goal as a machine learning researcher is to carry out data exploration, data cleaning, feature extraction, and developing robust machine learning algorithms that would aid them in the department.
