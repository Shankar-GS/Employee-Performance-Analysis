# Employee-Performance-Analysis

## Project Summary
INX Future Inc, one of the leading data analytics and automation sloution provide with over 15 years of global business presence.Recent years employee performance indexes are not healthy and this becomes a growing concern to the top mnagement and also client satisfaction level came down by 8 percentage points.Mr.Brain CEO initiate a data science project which analyses the current employee data and find the core underlying causes of this performance issue.

The following insights are expected from this project

* Data Visualization on a given Employee Performance Analytics dataset.
* Build and train predictive models which can predict employee performance based on various factors as inputs.
* Department wise performance based on various factors as inputs.
* Three most important factors impacting employee performance.
* Recommendations to improve the employee performance based on insights from the analysis.

## Requirement
The data can be downloaded from the below link http://data.iabac.org/exam/p2/data/INX_Future_Inc_Employee_Performance_CDS_Project2_Data_V1.8.xls

## Analysis
* In this dataset, the rows consist of all the employees and the columns describe parameters such as Age, Gender, EducationBackground etc. of the respective employees. These parameters will be referred to as features.
* Some of the columns have numerical values, as in the case of Age, DistanceFromHome etc. while the other have text-based (or categorical) values such as Gender, EducationBackground etc.
* In this kind of a scenario, where we have both numerical as well as categorical values, we use Label Encoding to better handle our datatypes. So, we also import the LabelEncoder and this will transform all the categorical features into numeric.
* Our task is to predict the Performance Rating of the employees (based on these ‘features’’), which forms our target variable.
* It turns out that it is a categorical one, consisting of essentially three values (2, 3 and 4), making it a typical classification problem.
* The Random Forest is chosen over other algorithms because it uses the entire dataset optimally which reduces bias error. The algorithm is also famous for providing maximum reduction in variance as it gives the average output from an ensemble of several decision trees; hence the name ‘Random Forest’.
* Additionally, we can also build a Decision Tree Classifier to help us visualize the situation better.
* Using the feature importance method on our classifier, we can infer that the feature which has the highest percentage affects the performance rating.

## Summary
I observe that

* The employee having the highest performance rating has greater environment satisfaction whereas the one having low rating has lesser environment satisfaction
* The employee with the highest performance rating has highest salary hike percentage
* The employee having the lowest performance rating is in the current position for a relatively longer period of time (implying slow career growth) and the one having the highest performance rating is going to be in the current position for a relatively shorter period of time (implying rapid career growth).

## Recommendations:
After careful evaluation of the observations, we can recommend the following to increase employee performance at an organization:

* Ensure a more improved rate of salary raises for the employees.
* Create a more friendly, comfortable and inclusive office environment.
* Help upgrade the skill sets of the current employees, so as to make them suitable to take up more responsibilities and challenges, and in turn, prepare them for promotions.
