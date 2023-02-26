## Employee Attrition Prediction by Machine Learning models

  This project aims to predict employee attrition using various machine learning algorithms such as logistic regression, random forest, SVM, and XGBoost. We will use a dataset containing various satisfaction_level	last_evaluation_rating	projects_worked_on	average_montly_hours	time_spend_company	Work_accident	promotion_last_5years	Department	salary	Attrition.
  
## Dataset

  The dataset used in this project contains a total of 1470 observations with 35 attributes. 
  The dataset is split into a training set and a testing set with 70% of the data used for training and 30% used for testing.

## Dependencies

    Pandas
    NumPy
    Scikit-learn
    Matplotlib
    Seaborn

## ML-Algorithms

  We will use the following machine learning algorithms for prediction:

    Logistic Regression
    Random Forest
    SVM
    XGBoost
    
## Cross Validation

  We will use 10-fold cross-validation to evaluate the performance of the machine learning models.
  
## Evaluation Metrics

  We will use the classification report to evaluate the performance of the machine learning models. 
  The classification report provides precision, recall, F1 score, and support metrics for each class.
  
## Project Architecture

  Data import
  Data exploration/Visualization
  Data clean up
  Feature selection using RFE
  Machine Learning Models
  10 Fold Cross validation
  Classification reports for all ML- models implemented
 
## Results

  We achieved the following results on the test set:

    Algorithm	             Precision    Recall	  F1 Score CV-Accuracy %
    Logistic Regression	      0.84	    0.88	  0.86      77
    Random Forest	              0.86	    0.84	  0.85      96.2
    SVM	                      0.84	    0.86	  0.85      89.1
    XGBoost	                      0.87	    0.85	  0.86      95.6

  The results show that all four algorithms have similar performance, with XGBoost achieving the highest F1 score. 
  However, the precision and recall values for all algorithms are quite similar. 
  Whereas Random Forest achieves highest accuracy of 96.2%.
  
## Future Work

    Experiment with other machine learning algorithms such as Neural Networks and Gradient Boosting Machines.
    Explore the dataset further to identify new features that may be predictive of employee attrition.
    Use feature selection techniques to identify the most important features for prediction.
    Deploy the trained models as a web application or a mobile app for easy and efficient use.
