Heart Disease Prediction Using Machine Learning

**Objective:** Develop a machine learning model to predict the likelihood of heart disease based on patient data. This project involves model training, evaluation, and hyperparameter tuning to achieve high prediction accuracy.

## Project Overview

In this project, we applied several machine learning models to predict heart disease:
- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**
- **Random Forest Classifier**

We also performed hyperparameter tuning using `RandomizedSearchCV` and `GridSearchCV` to optimize model performance.

## Results

- **Best Model:** Logistic Regression (tuned with GridSearchCV)
- **F1-score:** 0.867
- **Recall:** 0.921
- **Precision:** 0.821
- **Accuracy:** 0.845
- **Model Score:** 0.885

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/heart-disease-prediction.git

2. Navigate to the project folder:
   cd heart-disease-prediction

3. Create and activate the Conda environment:
   conda env create -f environment.yml
   conda activate heart-disease-env

4. Install additional dependencies if needed:
   pip install -r requirements.txt

   
