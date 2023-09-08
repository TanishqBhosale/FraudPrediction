# FraudPrediction
Explore groundbreaking data analysis and machine learning in our Bank Account Fraud Prediction project. Leveraging one of the largest datasets ever encountered, with a staggering 6.3 million rows, we employ cutting-edge techniques to safeguard financial transactions and protect against fraudulent activities
# Bank Account Fraud Prediction Data Analysis and Machine Learning
Welcome to the Bank Account Fraud Prediction project, a data analysis and machine learning endeavor. In this project, we analyze a massive dataset comprising 6.3 million rows to predict bank account fraud. Below, we'll provide an overview of the key elements of this project.

## Project Description
Dataset Size: This project utilizes one of the largest datasets ever encountered, containing a staggering 6.3 million rows of data.

Python Libraries: We use several Python libraries, including Pandas, Scikit-Learn, Seaborn, Matplotlib, LightGBM, and more, to perform data analysis and machine learning tasks.

## Code Overview
The provided code is a Jupyter Notebook (Fraud.ipynb) that you can access via the following link: Fraud.ipynb.

Here's a brief outline of the code's sections:

Data Loading: We load the dataset from Google Drive to analyze and process it.

Data Preprocessing: We perform data preprocessing tasks, including handling missing values and outliers. We also encode categorical variables and normalize numerical features like 'amount,' 'oldbalanceOrg,' 'newbalanceOrig,' 'oldbalanceDest,' and 'newbalanceDest.'

Data Visualization: We create visualizations to explore the relationships and correlations within the dataset. Heatmaps and scatter plots help us understand the data better.

Handling Outliers: We identify and visualize outliers in the numerical columns using box plots and scatter plots.

Interquartile Range (IQR) Outliers: We detect and analyze outliers using the IQR method.

Z-Score Outliers: We identify outliers based on Z-scores and remove them from the dataset.

Data Splitting: We split the cleaned dataset into training and testing sets for machine learning model training.

Model Selection: We use the PyCaret library to explore and compare different machine learning models to predict fraud.

## Machine Learning Models
We employ various machine learning models to predict fraud, including:

Light Gradient Boosting Machine (LightGBM): We train a LightGBM classifier to predict fraudulent activities.

Random Forest Regressor: We use a Random Forest Regressor to model and predict fraud in the dataset.

## Conclusion
This project aims to provide insights into bank account fraud prediction using a large dataset and machine learning techniques. Feel free to explore the code in the provided Jupyter Notebook for more details on data analysis and model performance.

Please make sure to replace the placeholders with actual links, if applicable, and customize the readme further according to your project's needs.
