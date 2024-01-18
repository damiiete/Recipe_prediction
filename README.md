# Recipe_prediction
This project was done as part of my DataCamp Data Scientist Professional Certification exam. Tasty Bytes, a company providing recipes for people during covid. The product manager aims to predict recipes that cause high traffic on the site when posted.

## Description of Task

The task involves automating the selection of a featured recipe for the homepage. Historically, opting for a popular recipe has led to a notable uptick in overall website traffic, reaching up to 40%. The challenge lies in predicting the popularity of recipes to make informed selections. Addressing this, the notebook's completed task showcases the the development of a model with the ability to:

- Predict recipes that will result in high traffic.
- Achieve an impressive 80% accuracy in predicting high-traffic recipes. This accomplishment is crucial as it directly impacts the company's goal of increasing subscriptions through enhanced website engagement.

## Solution
I performed a comprehensive analysis on the dataset, exploring various variables that could impact the website's traffic. The objective was to train classification models for predicting high-traffic recipes.

Two models were utilized for this task: the baseline model, Logistic Regression, and the comparative model, RandomForestClassifier.

Although the Logistic Regression model showed a slight edge, with a difference of less than 1%, the preferred choice is the Random Forest model. This preference is based on its capability to effectively handle non-linear relationships observed in the dataset.

For a deeper dive into the analysis, models, and results, please consult the associated notebook.
