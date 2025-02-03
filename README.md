# Data-Analytics-and-Visualization-Accenture

## Social Buzz Data Analysis Project
### Overview
Welcome to the Social Buzz Data Analysis Project! This project aims to analyze the content categories on Social Buzz and identify the top 5 categories with the largest popularity scores. This repository contains all necessary data files, the data model, and the steps followed to complete this analysis.

### Project Objectives
Understand the Data: We have seven datasets and a data model that shows relationships between these datasets. The goal is to identify which datasets are necessary to answer our business question.
Data Cleaning: Remove missing values, change data types where necessary, and remove irrelevant columns.
Data Modelling: Merge datasets to create a final dataset that can be used to identify the top 5 content categories based on popularity scores.
Analysis and Visualization: Generate insights and visualizations to present the findings.

### Steps Followed
1. Requirements Gathering
We need to determine the top 5 content categories with the largest popularity scores. The popularity is quantified by the “Score” given to each reaction type. Therefore, we require data showing the content ID, category, content type, reaction type, and reaction score.

2. Data Cleaning
Removed rows with missing values.
Changed data types where necessary.
Removed irrelevant columns.
3. Data Modelling
Merged the Reaction, Content, and Reaction Types tables.
Used the Reaction table as the base.
Joined relevant columns from the Content dataset.
Joined relevant columns from the Reaction Types dataset.
Calculated the total scores for each category to determine the top 5 performing categories.
4. Analysis and Visualization
Generated a cleaned dataset.
Created a pie chart showing the percentage share of the top 5 categories.
Analyzed additional insights such as the month with the most posts and the number of unique categories.
### Results
Cleaned Dataset: The final dataset containing all necessary information.
Top 5 Categories: Identified the top 5 categories with the highest popularity scores.
Visualizations
Pie Chart: Shows the percentage share of the top 5 content categories.
Bar Chart: Displays the number of posts per month.
Additional Insights: Including the month with the most posts and the number of unique categories.
