# 🏥 Insurance Cost Prediction Using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-red)
![R² Score](https://img.shields.io/badge/R²%20Score-0.7988-brightgreen)

## 📌 Overview

Healthcare costs vary significantly based on an individual's demographic and lifestyle factors. Predicting insurance charges accurately can help insurance companies assess risk, optimize premium calculations, and improve decision-making processes.

This project applies Machine Learning techniques to predict medical insurance charges using factors such as age, BMI, smoking status, gender, number of children, and residential region. The project includes complete data preprocessing, exploratory data analysis, feature engineering, statistical analysis, model development, and performance evaluation.

---

## 🎯 Problem Statement

Insurance providers need reliable methods to estimate medical insurance charges based on customer information. Manual estimation can be inconsistent and inefficient.

The objective of this project is to develop a Machine Learning model capable of predicting insurance costs using customer demographic and health-related attributes.

---

## 📊 Dataset Information

The dataset contains information about insurance beneficiaries and their corresponding medical insurance charges.

### Features

| Feature | Description |
|----------|------------|
| age | Age of the beneficiary |
| sex | Gender of the beneficiary |
| bmi | Body Mass Index |
| children | Number of dependents covered by insurance |
| smoker | Smoking status |
| region | Residential region |
| charges | Medical insurance cost (Target Variable) |

---

## 🚀 Project Workflow

### 1. Data Collection

- Imported the insurance dataset
- Examined data structure and feature types
- Verified dataset integrity

### 2. Data Cleaning

- Checked for missing values
- Removed duplicate records
- Validated data consistency

### 3. Exploratory Data Analysis (EDA)

Performed comprehensive analysis using:

#### Univariate Analysis

- Histograms
- Count Plots
- Distribution Plots

#### Bivariate Analysis

- Scatter Plots
- Box Plots
- Relationship Analysis

#### Multivariate Analysis

- Correlation Heatmaps
- Feature Interaction Analysis

---

## ⚙️ Data Preprocessing

### Categorical Feature Encoding

Applied encoding techniques on:

- Sex
- Smoker Status
- Region

### Feature Scaling

Implemented StandardScaler to normalize numerical features and improve model performance.

---

## 🧠 Feature Engineering

A new BMI Category feature was created based on BMI values:

| BMI Range | Category |
|------------|----------|
| < 18.5 | Underweight |
| 18.5 - 24.9 | Normal |
| 25 - 29.9 | Overweight |
| ≥ 30 | Obese |

These engineered features were further incorporated into model training.

---

## 📈 Statistical Analysis

To understand feature importance and relationships, the following statistical methods were applied:

### Pearson Correlation Analysis

Used to measure linear relationships between numerical variables.

### Chi-Square Test

Used to analyze dependency between categorical features.

---

## 🤖 Machine Learning Model

### Algorithm Used

**Linear Regression**

Linear Regression was selected as a baseline regression model to estimate insurance charges based on input features.

### Train-Test Split

- Training Data: 80%
- Testing Data: 20%

---

## 📊 Model Performance

The model was evaluated using:

### R² Score

| Metric | Score |
|----------|----------|
| R² Score | 0.7988 |

### Interpretation

- The model explains approximately **79.88%** of the variance in insurance charges.
- The achieved R² score indicates strong predictive capability for a Linear Regression model.
- The selected features capture a significant portion of the factors affecting medical insurance costs.

---

## 🔍 Key Insights

### 🚬 Smoking Status

Smoking was identified as the most influential factor affecting insurance charges.

### ⚖️ BMI

Individuals with higher BMI values generally incur higher medical insurance costs.

### 👨‍🦳 Age

Insurance charges tend to increase with age due to increased healthcare risks.

### 🏥 Obesity Risk

Obese individuals show significantly higher insurance expenses compared to other BMI categories.

---

## 💼 Business Applications

This project can be utilized in:

- Insurance Premium Estimation
- Healthcare Cost Forecasting
- Risk Assessment Systems
- Insurance Analytics Platforms
- Customer Segmentation
- Pricing Strategy Optimization

---

## 🛠️ Technologies Used

### Programming Language

- Python

### Libraries

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- SciPy

### Development Environment

- Jupyter Notebook

---

## 📂 Project Structure

```text
Insurance-Cost-Prediction/
│
├── insurance.ipynb
├── insurance.csv
├── README.md
├── requirements.txt
├── .gitignore
└── images/
```

---

## ⚡ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/Insurance-Cost-Prediction.git
```

Navigate to the project directory:

```bash
cd Insurance-Cost-Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

## ▶️ Running the Project

Open the notebook and execute all cells:

```bash
jupyter notebook insurance.ipynb
```

---

## 🎯 Learning Outcomes

Through this project, the following Machine Learning concepts were applied:

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Statistical Analysis
- Feature Encoding
- Feature Scaling
- Linear Regression
- Model Evaluation
- Business Insight Extraction

---

## 🔮 Future Enhancements

Potential improvements include:

- Random Forest Regressor
- XGBoost Regressor
- Gradient Boosting Regressor
- Hyperparameter Tuning
- Model Serialization using Joblib
- Streamlit Web Application Deployment
- Real-Time Insurance Cost Prediction Dashboard

---

## 👨‍💻 Author

### Sarthak Debata

B.Tech in Electronics and Instrumentation Engineering  
National Institute of Technology Rourkela

---

## ⭐ Project Summary

Developed an end-to-end Machine Learning pipeline for predicting medical insurance charges using demographic and health-related features. The project achieved an **R² Score of 0.7988**, demonstrating strong predictive performance while showcasing practical applications of data preprocessing, exploratory data analysis, feature engineering, statistical testing, and regression modeling.
