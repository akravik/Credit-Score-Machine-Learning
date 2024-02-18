# Credit-Score-Machine-Learning

***Overview***
This project focuses on predicting credit scores using machine learning algorithms. The end goal is to develop a predictive model that accurately estimates individuals' credit scores based on various demographic and financial factors. 

***Dataset***
The dataset used contains information such as age, gender, income, education level, marital status, number of children, home ownership status, and credit score. The dataset was sourced from Kaggle.

***Setup***
1. Clone the repository to your local machine.
2. Install the required libraries specified under the Imports section


***Features***
-Data cleaning to handle missing values and categorical variables
-Exploratory Data analysis techniques like pairplots and correlation heatmpaps are used to better understand relationships between variables
-Several Machine Learning Models are evaluated such as Logistic Regression, Decision Trees, Random Forests, etc and cross- validation is performed to determine the best model
-After the best model is selected, grid search using cross-validation is implemented to find the optimal hyperparameters
-The best model with the best hyperparameters is then evaluated and a classification report and accuracy metric are generated
-New data is used to test the model out and an accuracy >90% is achieved
