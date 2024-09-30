# Sparkify Project: Predicting User Churn

## Project Overview
Sparkify, a fictional music streaming startup, aims to predict user churn using Apache Spark. In this context, "churn" refers to customers leaving the service over a given period. Identifying potential churners is crucial, as acquiring new customers can cost five to six times more than retaining existing ones.

[Go to blog post!]([https://medium.com/@anhchu1291/churn-prediction-for-music-hosting-service-sparkify-5a8d476e5b9b](https://medium.com/@esdraswandji/how-to-save-millions-by-spotting-churning-customers-in-streaming-platforms-bdb4ef7b2179))

### User Types and Churn Definition
- Free plan users: Stream music with ads
- Paid plan users: Ad-free music streaming
- User actions: Thumb up/down songs, create playlists, add friends
- Churn types:
  1. Downgrade: Paid to free plan
  2. Cancel: Stop using the service entirely

## Project Goal
Develop a machine learning model to accurately identify potential churners of both types (downgraded and cancelled users) based on their interaction data.

## Key Points
- Data: 12GB log file with 18 fields per user interaction
- Tools: Apache Spark, PySpark MLlib 
- Process: Data loading, exploration, feature creation, model building, churn prediction
- Models Tested: Logistic Regression, Support Vector Machine and Gradient Boosted Trees
- Best Model: Tuned Logistic Regression

## Project Significance
- Addresses critical business challenge of customer retention
- Demonstrates handling of large datasets with Spark
- Applies machine learning techniques to real-world problem

## Results
The winning model effectively identifies users at risk of churning, enabling targeted retention strategies to potentially save millions in revenue.
