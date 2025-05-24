# Hybrid Movie Recommendation System

A hybrid movie recommendation system that integrates content-based filtering and supervised machine learning to suggest movies and predict user preferences.

## Files
- `movierecommender_corrected.ipynb` — Jupyter Notebook implementing the complete hybrid recommender pipeline.
- `movies.csv` — Dataset containing movie metadata for similarity-based recommendations.

## Techniques Used
- **Content-Based Filtering**: Recommends movies based on cosine similarity of movie metadata.
- **Machine Learning Models**:
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Support Vector Machine (SVM)
  - Naive Bayes
- **Model Evaluation**:
  - Confusion Matrix (classification accuracy)
  - ROC Curve and AUC Score (binary classification performance)

## Features
- Combines content-based and model-based recommendations.
- Predicts movie ratings using trained classifiers.
- Visualizes model performance with seaborn and matplotlib.
- Handles missing movie entries gracefully.

## Libraries Used
- `pandas`, `numpy` for data processing
- `scikit-learn` for ML models and evaluation
- `seaborn`, `matplotlib` for visualization
