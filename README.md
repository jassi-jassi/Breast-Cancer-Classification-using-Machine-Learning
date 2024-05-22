# Breast-Cancer-Classification-using-Machine-Learning
This repository contains a machine learning project for classifying breast cancer using various algorithms. The goal is to develop a predictive model that can accurately determine whether breast cancer is benign or malignant based on features computed from digitized images of fine needle aspirate (FNA) of a breast mass.
# Breast Cancer Classification using Machine Learning

## Dataset

The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) Data Set, which is publicly available on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)). The dataset contains 569 instances with 30 features each, including:

- Radius (mean of distances from center to points on the perimeter)
- Texture (standard deviation of gray-scale values)
- Perimeter
- Area
- Smoothness (local variation in radius lengths)
- Compactness (perimeter^2 / area - 1.0)
- Concavity (severity of concave portions of the contour)
- Concave points (number of concave portions of the contour)
- Symmetry
- Fractal dimension ("coastline approximation" - 1)

The target variable is a binary classification indicating whether the cancer is benign (0) or malignant (1).

## Project Structure

- `data/`: Contains the dataset.
- `notebooks/`: Jupyter notebooks for data exploration, preprocessing, and model training.
- `models/`: Saved models for easy loading and evaluation.
- `scripts/`: Python scripts for data preprocessing, training, and evaluation.
- `results/`: Outputs of model evaluation, including performance metrics and visualizations.
- 
The primary libraries used in this project include:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- jupyter

This script will preprocess the data, split it into training and testing sets, and train several machine learning models including:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Gradient Boosting
