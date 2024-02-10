# Project: Finding Donors for CharityML - Supervised Learnnig

In this project, I used sklearn and supervised learning techniques on data collected from the U.S. census to help a fictitious charity organization identify people most likely to donate to their cause. 

Frist, I investigated the factors that affect the likelihood of charity donations being made. Then, I used a training and predicting pipeline to evaluate the accuracy and efficiency/speed of three supervised machine learning algorithms (Gradient Boosting Classifier, Random Forest Classifier, Support Vector Machines (SVM)). I then proceed to fine tune the parameters of the algorithm that provides the highest donation yield. Finally, I also explored the impact of reducing number of features in data.

## Project Details
This project is designed to become acquainted with the many supervised learning algorithms available in sklearn, and to also provide for a method of evaluating just how each model works and performs on a certain type of data. It is important in machine learning to understand exactly when and where a certain algorithm should be used, and when one should be avoided.

Things learned by completing this project:
- How to identify when preprocessing is needed, and how to apply it.
- How to establish a benchmark for a solution to the problem.
- What each of several supervised learning algorithms accomplishes given a specific dataset.
- How to investigate whether a candidate solution model is adequate for the problem.

## Analysis and Statistics
Transforming Skewed Continuous Features
[Logarithmic transformation](https://en.wikipedia.org/wiki/Data_transformation_(statistics))  
Normalizing Numerical Features - Scaling  
[sklearn.preprocessing.MinMaxScaler](http://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.MinMaxScaler.html)  
One-hot Encoding Scheme  
[pandas.get_dummies()](http://pandas.pydata.org/pandas-docs/stable/generated/pandas.get_dummies.html?highlight=get_dummies#pandas.get_dummies)  
Shuffle and Split Data
[sklearn.model_selection](), [train_test_split]()  
Evaluating Model Performance  
Metrics and the Naive Predictor
Naive Predictor Performace  
Model Application  
Supervised Learning Models  
The following are some of the supervised learning models that are currently available in scikit-learn that you may choose from:

Gaussian Naive Bayes (GaussianNB)  
Decision Trees  
Ensemble Methods (Bagging, AdaBoost, Random Forest, Gradient Boosting)  
K-Nearest Neighbors (KNeighbors)  
Stochastic Gradient Descent Classifier (SGDC)  
Support Vector Machines (SVM)  
Logistic Regression  
Implementation - Creating a Training and Predicting Pipeline  
sklearn.metrics, fbeta_score, accuracy_score  
Implementation: Initial Model Evaluation  
sklearn.svm import SVC  
sklearn.ensemble import RandomForestClassifier, GradientBoostingClassifier  
Improving Results  
Implementation: Model Tuning  
sklearn.model_selection import GridSearchCV  
sklearn.metrics import make_scorer, r2_score, fbeta_score  
Final Model Evaluation

## Software and Packages

[Python 2.7](https://www.python.org/download/releases/2.7/)  
[NumPy](http://www.numpy.org/)   
[Pandas](http://pandas.pydata.org/)  
[scikit-learn](http://scikit-learn.org/stable/)  
[matplotlib](http://matplotlib.org/)  

[Jupyter Notebook](http://ipython.org/notebook.html)  

## Files

census.csv  
visuals.py

