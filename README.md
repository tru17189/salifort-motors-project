# salifort-motors-project
Utilized machine learning and Python to analyze Salifort's HR data, predicting employee turnover likelihood and identifying key factors influencing employee satisfaction.

## Overview
In this project, I developed a random forest model to predict Salifort's employee turnover using HR data from Salifort. This project consisted of four stages; as a matter of fact, the project was developed using the PACE work methodology, so the project's stages consisted of plan, analysis, construct, and execution. 

As part of the analysis stage, many visualizations were conducted in order to understand the nature of the data. Through the construct stage, I developed a random forest model. After analyzing the case, I determined that the Random Forest model was the most appropriate for this case, given its assumptions and compatibility with the data.

The final Random Forest model demonstrated outstanding performance, achieving an impressive F1 score of 0.94, indicating its robustness and accuracy in predicting churns.

## Business Understanding
A high turnover rate can be prejudicial for any company because it means that the company has to invest money and time in training employees who may not stay with the company. Salifort has had this problem recently. In order to solve it, they are looking to improve satisfaction levels. Therefore, Salifort is interesting in understanding which factors make an employee more likely to leave the company. Increased satisfaction levels in Salifort will mean that the company can spend less money on training new personnel, and the HR department can be more focused on work to increase employee satisfaction. 

## Data understanding
The Salifort data came from Coursera.org. (The scenario presented in this project is hypothetical.) The data consisted of approximately 15k entries and 10 features. The features included information about the employees on their satisfaction level, last evaluation, number of projects, average monthly hours, time spent at the company, work accident (yes/no), left (yes/no), promotion last 5 years (yes/no), department, and salary.

## Modeling and evaluation
The random forest model, which consists of 100 decision trees, was used to determine feature importance in determining which factor led an employee to leave. The model determined that the number of projects the employees work on, the years they have worked in the company (the lower the number, the higher the importance), and the average number of hours they have worked per month are features that have more weight in the employees' satisfaction level. The overall model performed with 98.3% accuracy and 98.1% precision. 

## Conclusion
This model is ready to predict employees' turnover. Salifort has to focus on increasing its satisfaction levels in order to keep turnover levels down. Employees that have less time in the company (under 5 years) and have a high number of projects are more likely to leave the company. Salifort can reward this type of employee in the way they consider best in order to make them feel appreciated by the company. Anyway, it seems that the differential factor that makes this type of employee leave the company is the lack of opportunities. We know this because the employees who have passed the fourth year at the company and received a promotion increase their satisfaction level significantly. As a matter of fact, most of the employees with more than 5 years in the company report higher levels of satisfaction. 
