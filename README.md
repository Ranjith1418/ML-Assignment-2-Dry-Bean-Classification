# Dry Bean Classification — M.Tech AIML Assignment 2

## Problem statement
Compare five machine-learning classifiers for predicting dry bean variety from numerical measurements and demonstrate evaluation in a Streamlit application.

## Dataset description
UCI Dry Bean Dataset (dataset ID 602): 13,611 instances, 16 numerical input features and seven target classes. Official source: https://archive.ics.uci.edu/dataset/602/dry+bean+dataset

## Models
Logistic Regression, Decision Tree, K-Nearest Neighbors, Gaussian Naive Bayes and Support Vector Machine (RBF).

## Evaluation
The notebook calculates Accuracy, weighted one-vs-rest AUC, weighted Precision, weighted Recall, weighted F1 Score and MCC. Populate the comparison table and observations from your actual notebook output; do not invent results.

## Results table
| Model | Accuracy | AUC | Precision | Recall | F1 | MCC |
|---|---:|---:|---:|---:|---:|---:|
| Logistic Regression | Run notebook | Run notebook | Run notebook | Run notebook | Run notebook | Run notebook |
| Decision Tree | Run notebook | Run notebook | Run notebook | Run notebook | Run notebook | Run notebook |
| KNN | Run notebook | Run notebook | Run notebook | Run notebook | Run notebook | Run notebook |
| Naive Bayes | Run notebook | Run notebook | Run notebook | Run notebook | Run notebook | Run notebook |
| Support Vector Machine | Run notebook | Run notebook | Run notebook | Run notebook | Run notebook | Run notebook |

## Observations
Write model-specific observations using the measured results and classification reports. Identify the winner based on weighted F1 Score and explain the trade-offs.

## GitHub Repository Link
Add your own repository URL after publishing your project.

## Live Streamlit App Link
Add your deployed Streamlit Community Cloud URL after deployment.

## Run
1. Install dependencies with `pip install -r requirements.txt`.
2. Run the notebook from top to bottom to generate the dataset, model files and test_data.csv.
3. Run `streamlit run app.py`.
4. Upload test_data.csv and select a model.

## Files
`ML_Assignment_2_Dry_Bean.ipynb`, `app.py`, `requirements.txt`, `README.md`, generated `dry_bean_dataset.csv`, `test_data.csv`, `model_comparison.csv`, and the five saved pipelines in `model/`.

## Reproducibility
The notebook uses a stratified 80/20 split with random_state=42. All models use the same split. Preprocessing is fitted only on training data. The Streamlit app does not retrain on uploaded test data.
