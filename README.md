## Overview

This project presents a complete data analytics and machine learning workflow using a healthcare stroke dataset. The objective is to explore factors associated with stroke occurrence and build predictive models using classification, regression, and clustering techniques.

The project follows a structured analytics pipeline:

1. Descriptive Analytics
2. Data Preparation
3. Classification
4. Regression
5. Clustering

---

## Dataset

The dataset contains patient health information including:

- Gender
- Age
- Hypertension
- Heart Disease
- Marital Status
- Work Type
- Residence Type
- Average Glucose Level
- BMI
- Smoking Status
- Stroke Status

The target variable is:

- **Stroke (0 = No Stroke, 1 = Stroke)**

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-Learn (SMOTE)

---

## Project Structure

```
Group_AU_Programming_for_Data_Analysis_and_AI_Coursework.ipynb
README.md
healthcare-dataset-stroke-data.csv
```

---

## 1. Descriptive Analytics

The project begins with exploratory data analysis (EDA), including:

- Data inspection
- Summary statistics
- Missing value analysis
- Distribution analysis
- Categorical feature analysis

### Visualizations

- Box Plots
- Violin Plots
- Bar Charts
- Heatmaps

---

## 2. Data Preparation

Data preprocessing includes:

### Missing Value Handling

- BMI value imputation

### Feature Engineering

- Data transformation
- Feature creation

### Encoding

Categorical variables are converted into numerical format using encoding techniques.

### Scaling and Normalization

Numerical features are standardized for model training.

### Outlier Removal

Outliers are identified and removed from:

- BMI
- Average Glucose Level

---

## 3. Classification Models

The project compares several machine learning classifiers for stroke prediction.

### Models Used

- Logistic Regression
- Support Vector Classifier (SVC)
- Decision Tree Classifier
- K-Nearest Neighbors (KNN)
- Random Forest Classifier

### Class Imbalance Handling

The project applies:

- SMOTE (Synthetic Minority Oversampling Technique)

to improve model performance on the minority stroke class.

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## 4. Regression Analysis

Regression models are used to analyze relationships between healthcare variables and continuous outcomes.

Evaluation metrics include:

- R² Score
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## 5. Clustering

Unsupervised learning techniques are used to identify hidden patterns within the healthcare dataset.

### Clustering Models

#### K-Means Clustering

Used to group patients based on similar health characteristics.

#### DBSCAN

Density-based clustering for discovering natural patient groups and outliers.

---

## Machine Learning Workflow

```text
Data Collection
      ↓
Descriptive Analytics
      ↓
Data Cleaning
      ↓
Feature Engineering
      ↓
Data Preparation
      ↓
Classification
      ↓
Regression
      ↓
Clustering
      ↓
Model Evaluation
```

---

## How to Run

### Clone the Repository

```bash
git clone https://github.com/yourusername/stroke-prediction-data-analytics.git
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
```

### Open the Notebook

```bash
jupyter notebook Group_AU_Programming_for_Data_Analysis_and_AI_Coursework.ipynb
```

### Run All Cells

Execute all notebook cells sequentially.

---

## Key Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Feature Engineering
- Data Visualization
- Predictive Analytics
- Classification
- Regression
- Clustering
- Healthcare Data Analysis
- Machine Learning Model Evaluation

---

## Authors

Aliyu Yakubu Suleiman  
MSc Artificial Intelligence and Machine Learning  
University of Portsmouth
