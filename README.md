Hackathon Project - Improving Employee Performance Prediction
This repository contains the implementation of a machine learning solution developed during a hackathon. The objective was to improve the accuracy of a supervised learning model for predicting employee performance using the provided dataset.

Problem Statement
The task was to build and optimize a predictive model for employee performance based on a dataset with the following input features:

Department
Gender
Age
Job Title
Hire Date
Years at Company
Education Level
Performance Score
Monthly Salary
Work Hours Per Week
Projects Handled
Overtime Hours
Sick Days
Remote Work Frequency
Team Size
Training Hours
Promotions
Employee Satisfaction Score
Resigned
The target variable was employee performance.

Approach and Solution
Feature Selection
To identify the most relevant features:

Analyzed the regression results report.
Compared feature significance using p-values to measure the strength of input features' relationship with the target variable.
Model Building and Optimization
Simple Linear Regression:
Initial implementation yielded an R² score of approximately 0.22.
Stochastic Gradient Descent (SGD) Linear Regression:
Applied to improve results, but no significant improvement was observed.
Polynomial Regression:
Achieved an R² score of 0.6555, significantly improving model performance.
Results
The best-performing model was Polynomial Regression, with an R² score of 0.6555, indicating a moderate fit for the dataset.

Technologies Used
Python
Libraries: NumPy, Pandas, Scikit-learn, Matplotlib
Conclusion
This project highlights the importance of feature selection and model experimentation in improving prediction accuracy. Polynomial regression proved to be the most effective approach for this problem.

Feel free to explore the code, provide feedback, or suggest further improvements!# Linear-Regression---First-Machine-Learning-Model
A simple project implementing linear regression to understand the basics of supervised learning. This beginner-level project focuses on data preprocessing, training, and visualizing results as part of my learning journey in machine learning.
