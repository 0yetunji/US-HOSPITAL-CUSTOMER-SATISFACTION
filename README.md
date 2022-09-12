# US-HOSPITAL-CUSTOMER-SATISFACTION
Understanding how patient satisfaction affects hospital ratings is necessary to improve clinical outcomes,  patient retention and quality of healthcare.
Over the years, the healthcare industry has moved from the orthodox concept of a noble profession towards a service industry where patient’s satisfaction is an important and effective indicator.
This Key Performance Indicator measures the quality of health care and the success of hospitals.
Bringing about a medium of hospitals accountability through their past records of overall ratings and performances.

Data Collection methodology:
Data was collected and downloaded from https://www.kaggle.com/datasets/abrambeyer/us-hospital-customer-satisfaction-20162020
Perform Data Wrangling
Perform Exploratory Data Analysis (EDA) with Visualizations using Python and PowerBI
Our Exploratory Data analysis highlighted the factors that might influence the change of the 
healthcare industry to a service-based industry.
Perform Feature engineering
Perform predictive analysis using classification models.
Tuning and Evaluating the best classification model for the trained dataset.

The data used in this analysis was collected and downloaded from Kaggle website.
The data was cleaned by checking for missing values, filling in missing values with “N” value where necessary and removing redundant columns.
The dataset consists of 5 CSV files each representing data for the release year between 2016 and 2020. Each file contained 43 columns of rating features and thousands of rows.

Performed some Exploratory Data Analysis (EDA) to find some patterns in the data and determine what would be the features for ranking the hospitals, state and cities, Label for training supervised models. 
Converted these features into numerical values with 3 meaning Above National Average , 2 meaning same as national average, 1 meaning Below National Average, 0 meaning Unavailable/Unapplicable.

Overal Performances of the Hospitals in terms of Facility Name, States and Cities was ranked top 10 across the 5 years.
The analysis showed that the hospital with the highest ranked performance across the five years was St. David’s Medical Centre.
In terms of the States, Rhode Island had the highest overall performance of hospitals in the United States with an overall performance score of 65.6 and Virgin Island at the far end of the list with an overall performance score of 32.8. 
In terms of the Cities, Holland City had the highest overall performance of hospitals in the United States with a score of 95.7 and Nome City at the far end of the list with a score of 0.00. 

## Predictive Analysis(Classification Models)
We created a column class from feature engineering, the data was standardized then a train/test split of the data was created.
And classification models such as Logistic Regression, K nearest neighbor, decision tree were used,using GridSearchCV to know the best hyperparameters for these models.Finally the best method was picked using the test data , and all these data gathered was use to draw out meaningful information.

## SUMMARY

Through the analysis it was found out that Decision Tree Classifier model was the best classifier model with the highest accuracy of 0.70 (70%) . This will help predict the Hospital overall rating at a high level of accuracy.
Patient Satisfaction is strongly correlated to hospital rating. 
It was also observed that the acute care hospitals performed better than critical access hospitals and Children’s Hospitals during the period.
Also the advent of the pandemic may have caused a decline in hospital performance. 
One of the major challenges we faced during the analysis of the data was the roughness of the data in terms of blank spaces which could have caused biased decisions by the analysts. 
It is recommended that in the future event of gathering the data from the hospitals survey, those questions that were not answered by a hospital should be noted ‘Not available’ rather than leaving it blank.
Is this analysis impactful?, yes it is , as it will help lots of people; hospital mangements, patients and investors to find answers to some of their crucial questions on the growth of hospitals performance.




