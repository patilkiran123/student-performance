# Student Performance Prediction Project  
In the dynamic field of education, gaining insights into student performance through thorough data analysis is vital for effective academic support. This project is dedicated to conducting in-depth data analysis on various features related to students' demographics, backgrounds, and academic engagement, with a focus on understanding patterns and trends. The objective is to extract valuable insights that inform strategies for enhancing academic intervention and support, fostering a deeper understanding of student performance dynamics.

## Problem Statement

In the dynamic landscape of education, understanding and predicting student performance is crucial for effective academic intervention and support.  
In this context, I have developed a machine learning model to predict the math scores of students based on various features related to their demographics, background, and academic engagement.

## Objective

The primary goal of this project is to create a predictive model that accurately estimates the math scores of students.  
The model leverages numerical features such as reading and writing scores, as well as categorical information including gender, race/ethnicity, parental level of education, lunch type, and test preparation course completion.

## Dataset

- The dataset provided contains information on student performance, with "math_score" as the target variable.
- The numerical columns include "reading_score" and "writing_score".
- The categorical columns encompass "gender," "race_ethnicity," "parental_level_of_education," "lunch," and "test_preparation_course".

## Overview

This project focuses on predicting math scores of students based on various demographic and academic factors. The machine learning model has been developed, evaluated, and deployed using AWS Elastic Beanstalk.

## Table of Contents

- [Data Exploration](#data-exploration)
- [Data Preprocessing](#data-preprocessing)
- [Feature Engineering](#feature-engineering)
- [Model Development](#model-development)
- [Model Evaluation](#model-evaluation)
- [Model Deployment on AWS Elastic Beanstalk](#model-deployment-on-aws-elastic-beanstalk)
- [Interpretation](#interpretation)
- [Recommendations](#recommendations)
- [To Run on local machine](#to-run-on-local-machine)

## Data Exploration

Conducted exploratory data analysis to understand the distribution and relationships within the dataset. Visualizations were used to gain insights into potential patterns or trends.

## Data Preprocessing

Handled missing or inconsistent data in the dataset and encoded categorical variables appropriately for machine learning algorithms.

## Feature Engineering

Explored the creation of new features or transformations to enhance the model's predictive power.

## Model Development

Chose and implemented machine learning algorithms suitable for regression tasks. The model was trained and optimized using the provided dataset.

## Model Evaluation

Assessed the model's performance using appropriate metrics such as mean squared error or R-squared. Cross-validation was employed to ensure the model's generalizability.

## Model Deployment on AWS Elastic Beanstalk

Deployed the trained machine learning model using AWS Elastic Beanstalk for scalability and ease of management. 

## Interpretation

Interpreted the model results and identified features that contribute significantly to predicting math scores.

## Recommendations

Provided recommendations and insights based on the model findings, suggesting potential areas for academic improvement.

## To Run on local machine

- Fork the Repo.

- Open Conda Cmd,Nagivate to the project location and  run the following,
> Code .

- the project folder will open in VScode.

- Open cmd line, run the following 
> conda create -p venv python==3.11 -y

- Then get inside the environment created
> conda activate venv\

- Then install the requirements.txt by typing the following in the cmd line
> pip install -r requirements.txt

- To predict run the following code
> python application.py

- Goto browser and open 
"http://127.0.0.1:5000/predictdata"

- Give the input in the web form the predication will be displayed.

