# Predict-Waze-User-Churn

## Project Overview

Consider that you are a Data professional at Waze. Waze’s free navigation app makes it easier for drivers around the world to get to where they want to go. Waze’s community of map editors, beta testers, translators, partners, and users helps make each drive better and safer. Waze partners with cities, transportation authorities, broadcasters, businesses, and first responders to help as many people as possible travel more efficiently and safely. 

You’ll collaborate with your Waze teammates to analyze and interpret data, generate valuable insights, and help leadership make informed business decisions. Your team is about to start a new project to help prevent user churn on the Waze app. Churn quantifies the number of users who have uninstalled the Waze app or stopped using the app. This project focuses on monthly user churn. In your role, you will analyze user data and develop a machine learning model that predicts user churn. 

This project is part of a larger effort at Waze to increase growth. Typically, high retention rates indicate satisfied users who repeatedly use the Waze app over time. Developing a churn prediction model will help prevent churn, improve user retention, and grow Waze’s business. An accurate model can also help identify specific factors that contribute to churn and answer questions such as: 

  * Who are the users most likely to churn?

  * Why do users churn? 

  * When do users churn? 

For example, if Waze can identify a segment of users who are at high risk of churning, Waze can proactively engage these users with special offers to try and retain them. Otherwise, Waze may simply lose these users without knowing why. 

Your insights will help Waze leadership optimize the company’s retention strategy, enhance user experience, and make data-driven decisions about product development.  

## Project Steps

This project is divided into 4 steps:

1. Exploratory Data Analysis : Waze’s data team is working on the churn project. The following tasks are needed before the team can begin the data analysis process - 
EDA and cleaning, Select and build visualization(s) type, Create plots to visualize variables and relationships between variables and Share your results with the data team

2. Hypothesis Testing : In this step you are asked to a conduct hypothesis testing on the data for the churn data. The data team has asked you to investigate Waze's dataset to determine which hypothesis testing method best serves the data and the churn project.

3. Build a Logistic Regression Model : The following tasks are needed at this stage of the project: Determine the correct modeling approach, Build a regression model, Finish checking model assumptions, Evaluate the model, Interpret model results and summarize findings for cross-departmental stakeholders within Waze

4. Build a Machine Learning Model : In this part, You will create the final machine learning model for the churn project. You will be responsible for leading these final tasks, which include feature engineering, model development, and evaluation. 

## Conclusion

In this project to find the model with the highest predictive power, the Waze data team developed two different models to cross-compare results: random forest and XGBoost along with a binary logistic regression model. The XGBoost model fit the data better than the random forest model. Additionally, it’s important to call out that the recall score (17%) is nearly double the score from the logistic regression model, while still maintaining a similar accuracy and precision score.

The ensembles of tree-based models in this project milestone are more valuable than a singular logistic regression model because they achieve higher scores across all evaluation metrics and require less preprocessing of the data. However, it is more difficult to understand how they make their predictions.

The ML models developed demonstrates a critical need for additional data in order to more accurately predict user churn.This modeling effort confirms that the current data is insufficient to consistently predict churn. It would be helpful to have drive-level information for each user(such as drive times, geographic locations, etc.). It would probably also be helpful to have more granular data to know how users interact with the app. For example, how often do they report or confirm road hazard alerts? Finally, it could be helpful to know the monthly count of unique starting and ending locations each driver inputs.
