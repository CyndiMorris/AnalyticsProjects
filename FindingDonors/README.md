# Project: Finding Donors for CharityML - Supervised Learning 

## Project Details
The [Finding Donors for CharityML](https://github.com/CyndiMorris/AnalyticsProjects/blob/main/FindingDonors/FindingDonors.ipynb) project is designed to become acquainted with the many supervised learning algorithms available in sklearn, and to also provide for a method of evaluating just how each model works and performs on a certain type of data. It is important in machine learning to understand exactly when and where a certain algorithm should be used, and when one should be avoided.

Things learned by completing this project:
- How to identify when preprocessing is needed, and how to apply it.
- How to establish a benchmark for a solution to the problem.
- What each of several supervised learning algorithms accomplishes given a specific dataset.
- How to investigate whether a candidate solution model is adequate for the problem.

## Analysis and Statistics

### Tasks & Questions:

**Naive Predictor Performance:**  
1. What would the model's accuracy and F-score be if we chose a model that always predicted an individual made more than $50,000?  

**Model Application:**  
1. List three supervised learning models appropriate for this problem.  
2. For each model chosen, describe a real-world application, its strengths, weaknesses, and why it's a good candidate for the problem.
 
**Choosing the Best Model:**  
1. Based on the evaluation performed earlier, explain which of the three models is most appropriate for identifying individuals making more than $50,000.
   
**Describing the Model in Layman's Terms:**  
1. Explain how the final model chosen works in layman's terms, including its major qualities such as training and prediction processes.
   
**Final Model Evaluation:**  
1. What are the optimized model's accuracy and F-score on the testing data?  
2. Are these scores better or worse than the unoptimized model?  
3. How do the results compare to the naive predictor benchmarks?
   
**Feature Relevance Observation:**
1. Of the thirteen available features in the dataset, which five features do you believe are most important for prediction, and in what order would you rank them?  
2. Why?
   
**Extracting Feature Importance:**
1. Train a supervised learning algorithm and extract feature importances to determine the top five most important features for the dataset.
   
**Effects of Feature Selection:**
1. How does the final model's performance on reduced data using only five features compare to the full data model's performance?  
2. Would you consider using the reduced data as the training set if training time was a factor?  

**Steps performed:**
1. Investigated the factors influencing charitable donation likelihood.
2. Established a training and prediction pipeline to evaluate the accuracy and efficiency of three supervised machine learning algorithms: Gradient Boosting Classifier, Random Forest Classifier, and Support Vector Machines (SVM).
3. Fine-tuned the parameters of the algorithm that generated the highest donation yield.
4. Explored the impact of reducing the number of features in the dataset.

### Supervised Learning Models: 

* Gaussian Naive Bayes (GaussianNB)  
* Decision Trees  
* Ensemble Methods (Bagging, AdaBoost, Random Forest, Gradient Boosting)  
* K-Nearest Neighbors (KNeighbors)  
* Stochastic Gradient Descent Classifier (SGDC)  
* Support Vector Machines (SVM)  
* Logistic Regression


## Dataset

The dataset was collected from the U.S. census to help a fictitious charity organization identify people most likely to donate to their cause. 

## Software and Packages

Python  
NumPy   
Pandas  
Scikit-learn  
Matplotlib   
Jupyter Notebooks
 
## Files

[census.csv](https://github.com/CyndiMorris/AnalyticsProjects/blob/main/FindingDonors/census.csv)  
[visuals.py](https://github.com/CyndiMorris/AnalyticsProjects/blob/main/FindingDonors/visuals.py)

