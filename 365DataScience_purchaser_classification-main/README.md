# 365DataScience_purchaser_classification
365 Data Science company's purchaser classification  

The classification of purchaser of 365 Data Science company based on their company dataset. The dataset has 7 features and 2 classes.    

Features - student_country	days_on_platform	minutes_watched	courses_started	practice_exams_started	practice_exams_passed	minutes_spent_on_exams  
Classes - purchased (1) and Not Purchased (0)  

The classification is performed using Logistic regression, K-Nearest Neighbors, Support Vector Machines, Decision Trees and Random Forest.  

The project flow:  
--> Import necessary libraries  
--> Import the data  
--> Plot Distribution of the features to study skewness  
--> Removing the data points which are outliers  
--> Distribution plots of features after removing datapoints which are outliers  
--> Calculating Variance influence factor to check multicollinearity  
--> Removing the features with VIF greater than or equal to 5 - practice_exams_started, practice_exams_passed  
--> Identifying and removing null values  
--> Creating input and target variables  
--> Implementing models with Confusion Matrix and Classification report  
--> Logistic Regression   
--> K-Nearest Neighbors - with GridSearchCV  
--> Support Vector Machines - with GridSearchCV  
--> Decision Trees - with GridSearchCV  
--> Random Forest - with GridSearchCV  

Decision Trees and Random Forest worked well with the dataset based on F1 score 

Further Improvement - The dataset is unbalanced. The number of purchased data points are more than the number of Not purchased data points. Balancing the dataset offers improvement.
