# Student Exam Pass Prediction System

## Project Description

The Student Exam Pass Prediction System is a machine learning project developed to predict whether a student is likely to pass or fail in the final examination. Educational institutions collect large amounts of student-related data, including study habits, attendance records, previous exam scores, parental education levels, and extracurricular participation. Analyzing this data manually is difficult and time-consuming.

This project uses Exploratory Data Analysis (EDA), Logistic Regression, and Dashboard Visualization to identify factors affecting student performance and support academic decision-making.

## Problem Statement

Educational institutions often face challenges in identifying students who are at risk of failing examinations. Students with low attendance, fewer study hours, weak academic history, or limited educational support may struggle in their final exams.

Failure to identify such students early may result in:

* Increased failure rates
* Poor academic performance
* Delayed academic intervention
* Reduced student confidence and motivation
* Lower institutional performance

Therefore, an automated prediction system is required to analyze student performance data and predict whether a student is likely to pass or fail.

## Objectives

### 1. Data Collection

* Load the student performance dataset from Kaggle.
* Understand dataset structure and available features.
* Identify numerical and categorical variables.

### 2. Data Cleaning and Preprocessing

* Check for missing values.
* Remove duplicate records.
* Verify data types.
* Encode categorical variables.
* Remove Student_ID from model training.
* Scale numerical features if required.

### 3. Descriptive Statistics

Calculate:

* Average study hours per week
* Average attendance rate
* Average past exam scores
* Average final exam score
* Pass vs Fail student count
* Gender-wise student distribution

### 4. Student Performance Analysis

Analyze:

* Pass vs Fail students
* Study habits of successful students
* Attendance patterns
* Previous exam performance
* Impact of internet access
* Participation in extracurricular activities

### 5. Group-Based Analysis

Study:

* Study Hours vs Pass/Fail
* Attendance Rate vs Pass/Fail
* Past Exam Scores vs Pass/Fail
* Gender vs Pass Rate
* Internet Access vs Pass Rate
* Parental Education Level vs Student Performance
* Extracurricular Activities vs Pass Rate

### 6. Relationship Analysis

Examine relationships between:

* Study Hours and Final Exam Score
* Attendance and Final Exam Score
* Past Exam Scores and Final Exam Score
* Parental Education and Student Performance
* Internet Access and Academic Achievement

### 7. Data Visualization

Create:

#### Bar Charts

* Pass vs Fail Distribution
* Gender Distribution
* Internet Access Distribution

#### Histograms

* Study Hours Distribution
* Attendance Rate Distribution
* Final Exam Score Distribution

#### Scatter Plots

* Study Hours vs Final Exam Score
* Attendance vs Final Exam Score

#### Box Plots

* Outlier Detection for Scores
* Attendance Comparison

#### Heatmaps

* Correlation Analysis among Numerical Features

### 8. Risk Analysis

Classify students into:

#### High Risk

* Low attendance
* Low study hours
* Low past exam scores

#### Medium Risk

* Average attendance and performance

#### Low Risk

* High attendance
* High study hours
* Strong previous academic performance

### 9. Predictive Modeling (Logistic Regression)

#### Independent Variables

* Gender
* Study_Hours_per_Week
* Attendance_Rate
* Past_Exam_Scores
* Parental_Education_Level
* Internet_Access_at_Home
* Extracurricular_Activities
* Final_Exam_Score

#### Dependent Variable

* Pass_Fail

#### Modeling Steps

* Encode categorical variables
* Split dataset into training and testing sets
* Train Logistic Regression model
* Predict Pass/Fail outcomes
* Calculate probability scores

### 10. Model Evaluation

Evaluate the model using:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix
* ROC-AUC Score

### 11. Dashboard Creation

Create an interactive dashboard using Plotly Dash or Streamlit.

#### Dashboard Components

* Pass vs Fail Distribution
* Study Hours Analysis
* Attendance Analysis
* Gender-wise Performance
* Internet Access Impact
* Parental Education Analysis
* Correlation Heatmap
* Student Risk Categories

#### Interactive Features

* Gender Filter
* Attendance Filter
* Study Hours Filter
* Pass/Fail Filter
* Dynamic Charts and KPIs

### 12. Insights and Conclusion

* Identify key factors affecting student success.
* Understand the importance of attendance and study habits.
* Analyze the impact of parental education and internet access.
* Detect at-risk students early.
* Support academic planning and intervention strategies.

## Dataset Information

### Dataset Source

Kaggle

### Dataset Name

Student Performance Prediction Dataset

### Features Used

* Student_ID
* Gender
* Study_Hours_per_Week
* Attendance_Rate
* Past_Exam_Scores
* Parental_Education_Level
* Internet_Access_at_Home
* Extracurricular_Activities
* Final_Exam_Score
* Pass_Fail

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Plotly
* Streamlit / Plotly Dash

## Expected Outcome

The system predicts whether a student is likely to pass or fail using Logistic Regression. It provides visual insights into student behavior, identifies risk categories, and helps educational institutions take timely action to improve academic performance.

## Conclusion

The Student Exam Pass Prediction System demonstrates how machine learning and data analytics can be used to support educational decision-making. By analyzing attendance, study habits, previous academic performance, and other influencing factors, the system helps identify students at risk and supports strategies for improving student success.


<img width="782" height="494" alt="Screenshot 2026-06-08 111818" src="https://github.com/user-attachments/assets/23fa5b0f-37f2-4376-ac50-505895296a4a" />



<img width="1044" height="715" alt="Screenshot 2026-06-08 111834" src="https://github.com/user-attachments/assets/1e76e4ff-a53a-45b8-a503-fb031a4398a9" />


<img width="825" height="584" alt="Screenshot 2026-06-08 111843" src="https://github.com/user-attachments/assets/c2b83bba-5eab-4377-8b60-67ca4ca132bf" />


<img width="824" height="464" alt="Screenshot 2026-06-08 111852" src="https://github.com/user-attachments/assets/e0ce721f-59a3-4450-9ebc-f135f0c78d39" />


<img width="1003" height="656" alt="Screenshot 2026-06-08 111901" src="https://github.com/user-attachments/assets/e61e5eb6-8f35-4017-9655-e0cdaca95c9b" />


<img width="588" height="462" alt="Screenshot 2026-06-08 111911" src="https://github.com/user-attachments/assets/7b1044f0-8e55-4f36-992c-96eb675525b9" />


<img width="921" height="582" alt="Screenshot 2026-06-08 111917" src="https://github.com/user-attachments/assets/8813501f-169f-496d-85ac-38c9f5a59bc6" />


<img width="940" height="579" alt="Screenshot 2026-06-08 111922" src="https://github.com/user-attachments/assets/34ffd67a-df11-4ac6-be89-b9b0a027d30e" />


<img width="905" height="558" alt="Screenshot 2026-06-08 111928" src="https://github.com/user-attachments/assets/0d26bb3f-f486-4e38-9554-b404a9ec3880" />


<img width="938" height="616" alt="Screenshot 2026-06-08 111934" src="https://github.com/user-attachments/assets/ef330715-49cf-460a-87be-c36bd726fa1e" />


<img width="964" height="593" alt="Screenshot 2026-06-08 111941" src="https://github.com/user-attachments/assets/192339f7-60f1-47f0-aa36-1157dbb40486" />


<img width="986" height="578" alt="Screenshot 2026-06-08 111949" src="https://github.com/user-attachments/assets/272f2024-7b08-4b50-ba00-9ea110065453" />
