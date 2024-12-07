Student Performance Analysis
This project aims to analyze student performance data using various machine learning techniques. It explores regression, classification, clustering, and ensemble methods to gain insights into factors influencing academic performance.

Dataset
The dataset used in this project is the StudentsPerformance.csv file, which contains information about students' gender, race, parental education level, lunch status, test preparation course, and scores in math, reading, and writing.

Prerequisites
Before running the code, ensure that you have the following libraries installed:

pandas
numpy
scikit-learn
catboost
matplotlib
seaborn
You can install these libraries using pip:

Usage
Clone the repository or download the code files.
Place the StudentsPerformance.csv dataset in the same directory as the code files.
Run the Jupyter Notebook or Python script containing the code.
Code Overview
The code covers the following aspects:

Data Preprocessing
Loading the dataset
Handling missing values
Encoding categorical variables
Feature selection
Regression Analysis
Implementing Random Forest Regression to predict student scores
Evaluating the model using mean squared error and R-squared score
Classification
Applying algorithms like Logistic Regression, CatBoost Classifier, Decision Tree, K-Nearest Neighbors, Random Forest, and Artificial Neural Network
Evaluating the models using accuracy, precision, recall, and F1-score
Clustering
Performing K-Means, Hierarchical, Mean Shift, and DBSCAN clustering
Evaluating the clusters using silhouette score and Davies-Bouldin index
Visualization
Generating confusion matrices
Plotting feature importance
Visualizing clusters
Creating heatmaps
