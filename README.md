# Wholesale Customer Analysis
## Project Overview
This project aims to analyze and understand the variations in the types of customers that a wholesale distributor interacts with. The dataset used in this project includes annual spending in monetary units across diverse product categories, providing valuable insights into customer behavior and preferences. The goal is to perform a detailed analysis that helps to describe the variation in customer types and develop a model that can effectively classify and cluster these customers.

## Dataset Information
### Context
The dataset refers to the clients of a wholesale distributor and includes their annual spending across various product categories, such as Fresh products, Milk, Grocery, Frozen products, Detergents_Paper, and Delicatessen. Understanding these spending patterns can help the distributor optimize their operations, tailor their marketing strategies, and better serve their customers.

## Project Tasks
The project is structured into several key steps:

1. Exploratory Data Analysis (EDA) 
    - Perform EDA: Explore the dataset to understand the distribution of the data, identify any outliers, and observe any patterns or correlations among the features.
    - Data Cleaning: If necessary, clean the data by handling missing values, correcting data types, or removing outliers.
2. Feature Scaling
    - Normalize the Data: Implement feature scaling using MinMaxScaler and StandardScaler.
    - Comparison: Compare the histograms/KDE plots for the scaled data using both scalers.
    - Selection: Choose the most appropriate scaler to proceed with the analysis. Provide reasoning for the selection based on the comparison results.
3. Feature Selection
    - RFECV Implementation: Use Recursive Feature Elimination with Cross-Validation (RFECV) to find the optimal number of features.
    - Plot Results: Generate a plot showing the number of features selected versus the cross-validation score, using the channel as the target variable.
4. Clustering Analysis
    - KMeans Clustering: Implement KMeans clustering for K values ranging from 2 to 15.
    - Elbow Method: Identify the optimal number of clusters using the elbow method, which helps determine the point where adding more clusters does not significantly improve the model.
5. Principal Component Analysis (PCA)
    - PCA Implementation: Perform PCA with the original number of features to reduce dimensionality.
    - Variance Explained: Analyze how much variance is explained by the first 2 and first 4 components.
    - Visualization: Visualize the clusters in the data using the principal components.
6. Model Implementation
    - XGBoost Classifier: Implement the XGBoost classifier with 5-Fold Cross-Validation to classify the customer data.
    - Performance Metrics: Report the performance metrics of the XGBoost model, including accuracy, precision, recall, F1-score, and any other relevant metrics.
## Conclusion
This project provides a comprehensive analysis of the Wholesale Customer dataset, focusing on understanding the variation among different customer types. By performing EDA, feature scaling, feature selection, clustering, and classification, the project aims to build a robust model that can classify and cluster customers effectively. The insights gained from this analysis can help wholesale distributors optimize their strategies and improve customer satisfaction.
