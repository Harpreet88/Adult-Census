Adult Census Dataset - Imputation Project

📌 Project Overview

This project explores different imputation techniques to handle missing data in the Adult Census dataset. The goal is to evaluate how various imputation methods impact data quality and predictive modeling performance.

📂 Dataset Details

Source: UCI Machine Learning Repository - Adult Census dataset

Target Variable: income

Induced Missingness: 10% missing values added to age and education-num

📊 Imputation Techniques Used

Regression Imputation

KNN Imputation

Iterative Imputation

📈 Evaluation Metrics

For Numerical Variables: RMSE (Root Mean Squared Error)

For Categorical Variables: Accuracy

Impact on Predictive Modeling: Random Forest Classifier/Regressor performance comparison

🔬 Key Steps

Introduce Missingness: Artificially introduce NaN values in age and education-num

Apply Imputation Methods: Use different techniques to fill missing values

Compare with Ground Truth: Evaluate imputation quality using RMSE and accuracy

Impact Analysis: Train a Random Forest model on original and imputed datasets to assess performance differences

📊 Results & Findings

Comparison of imputation techniques based on RMSE & accuracy

How imputation affects predictive model performance

Insights on the best imputation method for this dataset

🛠️ Tech Stack

Python: pandas, numpy, scikit-learn, seaborn, matplotlib

Jupyter Notebook: Data analysis and visualization

🚀 How to Run the Project


Install dependencies:

pip install -r requirements.txt

Run the Jupyter Notebook:

jupyter notebook

📌 Future Improvements

Explore Deep Learning-based imputation methods

Experiment with different predictive models to assess the impact of imputation

🤝 Contributing

Feel free to fork this repository, submit pull requests, or raise issues for discussion!

📩 Let's connect!LinkedIn | GitHub

