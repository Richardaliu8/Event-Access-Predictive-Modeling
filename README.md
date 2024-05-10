# Event-Access-Predictive-Modeling
Project Overview  
This project utilizes a dataset of event ticket purchases to predict whether access to an event will be granted. The analysis employs multiple machine learning methods including logistic regression, decision trees, and K-means clustering to explore how different factors such as ticket class, age, and price influence entry decisions.  

Features  
Data Exploration and Visualization: In-depth exploration of the Event_entry dataset using histograms, scatter plots, and box plots to visualize and understand the distribution of various features such as ticket class, sex, age, price, and bank balance.  
PCA Analysis: Implementation of Principal Component Analysis (PCA) to reduce the dimensionality of the dataset for logistic regression modeling. Models are trained and tested on reduced datasets with 2, 4, and 6 dimensions to evaluate the trade-off between computational efficiency and model accuracy.  
Logistic Regression and LASSO Comparison: Development of a logistic regression model to predict event entry, with a comparison to a LASSO logistic regression model to assess out-of-sample (OOS) performance and feature selection.  
Decision Tree Analysis: Application of a decision tree classifier to predict event entry. This includes preprocessing steps such as encoding categorical variables and handling missing data, with an explanation of the rationale behind each step.  
K-Means Clustering: Exploration of clustering using only the Age and Price variables. The analysis determines the optimal number of clusters (K) and visualizes the distribution of data points within these clusters to understand the segmentation of event attendees based on their age and ticket price.  

Purpose  
The goal of this project is to provide actionable insights into factors that influence event entry approvals and to develop predictive models that can help in planning and decision-making for event management. By understanding the patterns and correlations in the data, the project aids in enhancing the efficiency of ticket sales strategies and customer segmentation.  
