# Lead-Scoring-Case-Study

## Objective

An educational company named X Education sells online courses to industry professionals. On a typical day, numerous professionals interested in the courses visit their website to browse available offerings. The company promotes its courses across various websites and search engines like Google. Upon landing on the website, visitors may browse courses, fill out forms, or watch videos. Leads are generated when visitors provide their contact information, such as email addresses or phone numbers. Additionally, the company receives leads through past referrals. Once leads are acquired, the sales team initiates contact through calls, emails, etc. While some leads convert, the majority do not, resulting in a typical lead conversion rate of around 30% for X Education.

Despite acquiring many leads, X Education struggles with a poor lead conversion rate. For instance, out of 100 leads acquired in a day, only about 30 are converted. To enhance efficiency, the company aims to identify potential leads, also known as 'Hot Leads.' By effectively identifying these leads, the lead conversion rate is expected to increase as the sales team can prioritize communication with these high-potential leads rather than contacting everyone indiscriminately.

The objective is to build a logistic regression model to assign a lead score ranging from 0 to 100 to each lead. This score will enable the company to target potential leads more effectively, with higher scores indicating hotter leads likely to convert, while lower scores denote colder leads less likely to convert.

Additionally, the model should be flexible to accommodate any future changes in the company's requirements. It should address any problems or challenges presented by the company, adjusting accordingly based on the logistic regression model's outcomes. These adjustments should be documented and included in the final presentation for recommendations.

## Steps Followed

1. Data Reading: Importing the dataset containing lead information.
2. Data Cleaning: Removing or replacing irrelevant or missing values, handling duplicate data.
3. Exploratory Data Analysis (EDA): Analyzing the dataset to understand the distribution, relationships, and patterns in the data.
4. Creating Dummy Variables: Encoding categorical variables as dummy variables for modeling purposes.
5. Train-Test Split: Splitting the data into training and testing sets to train and evaluate the model.
6. Model Building: Utilizing logistic regression to build a predictive model for lead conversion.
7. Making Predictions: Predicting the likelihood of lead conversion using the trained model.
8. Model Evaluation: Assessing the performance of the model using various evaluation metrics such as accuracy, precision, recall, and F1-score.
9. ROC Curve: Plotting the Receiver Operating Characteristic (ROC) curve to visualize the trade-off between sensitivity and specificity.
10. Prediction on Test Set: Applying the model to the test dataset to make predictions on unseen data.
11. Precision-Recall Analysis: Evaluating the precision and recall of the model to understand its performance across different thresholds.


## Details of files given

The files provided for the Lead Score Case Study are:

1. Lead Score Case Study Lead Scoring.ipynb: This is a Jupyter Notebook file containing the code and data analysis conducted for the lead scoring case study.

2. Assignment Subjective Questions.pdf: This document contains answers to subjective questions related to the case study.

3. Lead Score Case Study.pdf: This is the final presentation summarizing the findings and recommendations from the lead scoring analysis.

4. Leads.csv: This CSV file contains the dataset used for the lead scoring analysis.

5. Leads Data Dictionary.xlsx: This Excel file provides a data dictionary describing the columns and their meanings in the Leads.csv dataset.

6. Summary.pdf: This document summarizes the work done in the Lead Score Case Study, providing an overview of the analysis and results obtained.
