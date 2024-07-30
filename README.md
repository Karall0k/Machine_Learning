# Machine_Learning

#Predicting MLB Batting Performance

Group Members:
Andrew Amato
Karesse Lockard
Steven Schiffner
Joshua Turk
Brian Morrissey


Objective: What batting statistic best predict hitter performance?  
In this analysis, a machine learning model was used to predict major league batter performance based on batter data from stathead.com and Statcast (via Kaggle.com). The data selected covers player batting statistics from 2017 – 2019. More recent data was not readily available, incomplete, or had too small of a sample size.

Data Cleaning Steps included:  
•	Load and clean the source datasets by removing unnecessary columns and renaming columns in preparation for a merge  
•	Merge the datasets into one dataframe and export as a .csv file  
•	Store the data and create a table using SQLite  

Machine Learning Model  
After evaluating multiple deep learning models, the Random Forest Model was selected to evaluate this dataset. The data was further prepared so that the random forest model can distinguishes above-average statistics (1) and below-average statistics (0) for the batting average and slugging average targets. 


