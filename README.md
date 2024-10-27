# A3-MLH

This project aims to predict the mortality rate of hospitalized patients following cardiac arrest using data from the MIMIC-IV database. We applied various machine learning models to analyze the impact of different clinical features on patient outcomes, with a particular focus on evaluating model performance using sensitivity, specificity, AUC, and likelihood ratios. 

## Project Structure

- **notebooks/EDA_and_Skewness_Handling.ipynb**: Contains Exploratory Data Analysis (EDA) and skewness handling, including feature selection and preprocessing steps for the dataset.
- **notebooks/MLH_GA.ipynb**: Contains the machine learning pipeline, including data processing, model training, nested cross-validation, and SHAP analysis for model interpretation.

## Model Evaluation

We evaluated the following models for predicting patient mortality:

- Decision Tree
- Naive Bayes
- K-Nearest Neighbors (KNN)
- Gradient Boosting Machine (GBM)
- Random Forest
- Logistic Regression
- MLP 

**Best Model**: Based on our evaluation metrics, the K-Nearest Neighbors (KNN) and Gradient Boosting Machine (GBM) models demonstrated strong performance in terms of AUC and sensitivity, making them suitable choices for healthcare applications where reducing Type II errors is critical.

## Contributors

- **Yantao Wang** (Student ID: 1347944)
- **Jiejun Xie** (Student ID: 1418316)
- **Jugyeong Kim** (Student ID: 1558392)
- **Biao Xiang** (Student ID: 1495970)

## Appendix

For the full code and documentation, refer to our [GitHub Repository](https://github.com/JKJIN1999/A3-MLH.git).
