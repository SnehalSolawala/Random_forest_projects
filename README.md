# Random Forest Projects

A collection of hands-on machine learning projects using **Random Forest** algorithms for both **regression** and **classification** tasks.

---

##  Project Overview

### 1. Car Price Prediction (Regression)
- **Notebook:** `car_price_prediction_random_forest_regressor.ipynb`  
- **Dataset:** `cardekho_imputated.csv`  
- **Description:**  
  Builds a Random Forest Regressor to predict car prices using the Cardekho dataset.  
  The dataset has been preprocessed—missing values handled and imputed appropriately.

- **Key Features:**  
  - Data cleaning & imputation  
  - Exploratory Data Analysis (EDA)  
  - Feature engineering  
  - Hyperparameter tuning (e.g., `n_estimators`, `max_depth`)  
  - Model evaluation using metrics like RMSE, MAE, R²  
  - Visualization of model performance

---

### 2. Random Forest Classification
- **Notebook:** `random_forest_classification.ipynb`  
- **Dataset(s):** Could be `Travel.csv` or others  
- **Description:**  
  Implements Random Forest Classification to predict categorical outcomes (e.g., travel preferences, churn) based on available features.

- **Typical Workflow:**  
  - Data loading and cleaning  
  - EDA with visualizations (like decision boundaries or class distributions)  
  - Model training, tuning, and validation  
  - Evaluation using classification metrics (accuracy, precision, recall, F1 score, ROC-AUC)

---

##  Additional Files

- **`auc.png`**: Visualization of the model’s ROC-AUC curve (likely from classification model)  
- **`Travel.csv`**: Probably the source dataset for the classification notebook

---

##  Getting Started

1. **Clone the Repository**
   ```bash
   git clone https://github.com/SnehalSolawala/Random_forest_projects.git
   cd Random_forest_projects


2. **Set Up Your Environment
    python3 -m venv env
    source env/bin/activate  # or `env\Scripts\activate` on Windows
    pip install -r requirements.txt

3. **Run the Notebooks
      jupyter notebook

    Open and run:

    car_price_prediction_random_forest_regressor.ipynb
    
    random_forest_classification.ipynb

##  Project Structure
  ├── auc.png
  ├── car_price_prediction_random_forest_regressor.ipynb
  ├── cardekho_imputated.csv
  ├── random_forest_classification.ipynb
  ├── Travel.csv
  └── README.md
