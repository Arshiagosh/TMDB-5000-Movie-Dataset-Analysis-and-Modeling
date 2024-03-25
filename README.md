# TMDB-5000-Movie-Dataset-Analysis-and-Modeling
This project aims to predict the success of movies using machine learning algorithms. It involves data preprocessing, exploratory data analysis (EDA), feature selection, and model training using various classification algorithms.

## Dataset

The dataset used in this project contains information about movies, including features such as budget, runtime, release year, and more. You can find the datasets in the `datasets.zip` file.

## Exploratory Data Analysis (EDA)

EDA involves analyzing the dataset to understand its characteristics and relationships between variables. Various visualizations and statistical analyses are performed to gain insights into the data.

## Feature Selection

Features are selected based on intuition and, in another approach, using Principal Component Analysis (PCA) to reduce dimensionality and improve model performance.

## Model Training

Several classification algorithms are trained and evaluated for predicting movie success, including:

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

The performance of each model is evaluated using metrics such as accuracy, precision, recall, F1-score, and ROC curves.

## Recommender System

A simple Plot description-based Recommender is implemented based on the `overview`. It uses TF-IDF.

## Usage

To use this project, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/Arshiagosh/TMDB-5000-Movie-Dataset-Analysis-and-Modeling
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Extract the datasets from datasets.zip.
4. Run the Jupyter notebook or Python scripts to explore the data, train models, and make predictions.
