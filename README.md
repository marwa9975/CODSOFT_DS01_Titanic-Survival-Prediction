# **Titanic Survival Prediction**

## **Project Overview**

The Titanic Survival Prediction project involves building a machine learning model to determine whether a passenger on the Titanic survived or not. This classic project utilizes the Titanic dataset, which contains detailed information about individual passengers, including their age, gender, ticket class, fare, cabin, and survival status. The primary goal is to create an accurate predictive model that can forecast passenger survival based on the available data.

## **Business Problem**

The business problem addressed in this project is to provide a reliable tool for predicting the likelihood of a passenger surviving the Titanic disaster. This predictive model can be valuable for historical analysis, understanding the factors contributing to survival, and potentially for future applications.

## **Project Objectives**

* Model Building: Construct and train a machine learning model to predict passenger survival.
* Model Evaluation: Assess the model's performance using appropriate metrics and evaluation techniques.

## **Data Understanding**

The dataset used in this project is sourced from Kaggle and includes the following columns:

1. PassengerId: Unique identifier for each passenger.
2. Survived: Binary variable (0 for not survived, 1 for survived).
3. Pclass: Ticket class (1st, 2nd, 3rd).
4. Name: Passenger's name.
5. Sex: Gender of the passenger.
6. Age: Age of the passenger (some missing values).
7. SibSp: Number of siblings or spouses on board.
8. Parch: Number of parents or children on board.
9. Ticket: Ticket number.
10. Fare: Passenger's fare (some missing values).
11. Cabin: Cabin number (many missing values).
12. Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

## **Data Preparation**

- Dealing with missing values
- Checking for duplicates
- Checking for outliers and handling them
- Dropping unnecessary columns

## **Exploratory Data Analysis**

### Univariate Analysis

- Survival rate
- Distribution Plots for numerical variables
- Bar plots for categorical variables

### Bivariate Analysis

- Survivors by Passenger Class
- Correlation Heatmap between Age and Fare
- Correlation Heatmap between Survived and Fare
- Numeric vs. Survival Analysis

### Multivariate Analysis

- Pair Plots
- Correlation Heatmap

## **Data Preprocessing**

- Assigning variables
- One-Hot Encoding of Categorical Variables
- Scaling Numerical Features
- Train-Test Split
- SMOTE (Synthetic Minority Over-sampling Technique) for addressing class imbalance

## **Modeling**

- Baseline Model: Logistic Regression
- Advanced Models: Support Vector Machine (SVM) and K-Nearest Neighbors (KNN)
- Hyperparameter Tuning for K-Nearest Neighbors (KNN)

## **Conclusions**
* Model Recommendation: The K-Nearest Neighbors (KNN) model is the recommended choice due to its superior performance on test data.
* Optimize Hyperparameters: Perform hyperparameter tuning, especially for KNN, to enhance performance metrics.
* Ticket Class Matters: First-class passengers had a higher survival rate, highlighting the impact of ticket class.
* Gender Significance: Gender strongly influenced survival, with females having a notably higher survival rate.
* Fare Correlation: Passengers who paid higher fares were more likely to survive, likely due to factors like ticket class and cabin location.


## **Next Steps**
* Feature Engineering: Explore additional feature engineering techniques to create new relevant features or transform existing ones. Feature selection methods can also be applied to identify the most important features for prediction.
* Model Deployment: After finalizing the predictive model, consider deploying it in a real-world scenario. Create a user-friendly interface for end-users to input passenger information and receive survival predictions
* Ensemble Modeling: Experiment with ensemble techniques, such as Random Forest or Gradient Boosting, to combine multiple models for potentially better prediction accuracy.

## **Next Steps**
* Feature Engineering
* Model Deployment
* Ensemble Modeling

## **Author**
- Marwa Osman
- marwaosman9975@gmail.com
- [LinkedIn](https://www.linkedin.com/in/marwa-osman-00190b222/)
- [GitHub](https://github.com/marwa9975)
