# ELE489_HW_2, Decision Tree Classifier on Banknote Authentication Dataset

This project applies a **Decision Tree Classification** algorithm to the [Banknote Authentication Dataset](https://archive.ics.uci.edu/ml/datasets/banknote+authentication), which contains extracted features from images of genuine and forged banknotes.

# Dataset Description

The dataset consists of 4 numerical features derived from wavelet-transformed images of banknotes:

- `Variance`
- `Skewness`
- `Kurtosis`
- `Entropy`

The target variable is binary:
- `0`: Forged note
- `1`: Genuine note

# Project Highlights

- **Exploratory Data Analysis (EDA):** Feature distribution, pairplots, and correlation heatmaps to understand data structure and separability.
- **Feature Evaluation:** Visual and statistical comparison of features to identify the most discriminative ones.
- **Model Training:** Training a `DecisionTreeClassifier` using various `criterion`, `max_depth`, and `min_samples_split` hyperparameters.
- **Model Evaluation:** 
  - Accuracy, Precision, Recall, and F1-score metrics
  - Confusion matrices
  - Feature importance visualization
- **Interpretability:** Discussion on model complexity, overfitting risks, and trade-offs between depth and generalization.

# Results

- Best accuracy achieved with:
  - `criterion='gini'`
  - `max_depth=6`
  - `min_samples_split=2`
- Most influential feature: `Variance`
- Less discriminative feature: `Entropy`

# Tech Stack

- Python
- scikit-learn
- matplotlib, seaborn
- pandas, numpy

# Hüseyin Talha ÇULHA 21947138
