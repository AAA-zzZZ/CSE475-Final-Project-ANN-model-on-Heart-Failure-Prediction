# CSE475-Final-Project-ANN-model-on-Heart-Failure-Prediction


## Overview:

This prepository presents an Artificial Neural Network (ANN) based approach to predict heart failure events using a clinical dataset consisting of 11 features. 
The project follows a structured machine learning workflow, including exploratory data analysis (EDA), model development and evaluation, analysis on model performance, outline for model deployment and ethical considerations.
The goal is not only achieve predictive performance, but also to assess the model behavior, capability and ethical implications in a real life healthcare context.

---
## Dataset:
This model uses the dataset [Heart Failure Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction). There are 918 observations, with 12 attributes(variables). Besides the target binary variable HeartDisease, there are 11 features that are clinically associated with cardiovascular health and heart failure risk. 

*   Age: Numerical
*   Sex: Categorical
*   ChestPainType: Categorical
*   RestingBP: Numerical
*   Cholesterol: Numerical
*   FastingBS:  Categorical
*   RestingECG: Categorical
*   MaxHR: Numerical
*   ExerciseAngina: Categorical
*   Oldpeak: Numerical
*   ST_Slope: Numerical

All analysis and modeling are conducted using this fixed feature set.


---
## Repository Structure

This project is staged into 3 Jupyter Notebooks, each corresponds to a phase in machine learning pipeline:

### 1. Exploratory Data Analysis(EDA)

Notebook: CSE 475 Final Project Milestone 1: Data Preperation
* Overview the dataset structure and the overall distribution of numerical variables
* Univariate and multivariate feature exploration
* Identify any missing values or outliters and handle them properly
* Normalize categorical variables 
* Integrate the cleaned dataset into the final dataset
* Analyze the interactions between different features
* Select distinct features and feature engineer

### 2. Model Development

Notebook: CSE 475 Final Project Milestone 2: Model Development 
* Select the most appropriate model for the dataset and justify the selection
* Model developing and training based on a provided examplar with split dataset
* Defining the architecture and the algorithm
* Quick analysis on the model performance with visualization curves to help interpretion
* Optimize model performances
* Train final model after validation
* Evaluate model on the test dataset with metrics

### 3. Model Evaluation and final report


