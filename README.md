# Health Analysis-Exploratory Data Analysis

## Project Overview

**Pulse of Prevention: Analyzing Heart Health for Better Outcomes** is a Python-based Data Analysis project focused on exploring heart-health data and identifying patterns associated with heart disease.

The project uses **Pandas, NumPy, Matplotlib, Seaborn, SciPy, and Scikit-learn** to perform data cleaning, exploratory data analysis, statistical analysis, visualization, and machine learning.

## Objectives

- Analyze patient heart-health data.
- Understand patient demographics and clinical measurements.
- Identify patterns associated with heart disease.
- Analyze important risk factors.
- Compare patients with and without heart disease.
- Identify correlations between variables.
- Detect potential outliers.
- Normalize numerical features.
- Build a Logistic Regression model.
- Evaluate the machine-learning model.

## Dataset

The project uses the `heart.csv` dataset.

### Important Columns

| Column | Description |
|---|---|
| `age` | Age of the patient |
| `sex` | Sex of the patient |
| `cp` | Chest pain type |
| `trestbps` | Resting blood pressure |
| `chol` | Serum cholesterol |
| `fbs` | Fasting blood sugar |
| `restecg` | Resting ECG result |
| `thalach` | Maximum heart rate achieved |
| `exang` | Exercise-induced angina |
| `oldpeak` | ST depression |
| `slope` | Slope of peak exercise ST segment |
| `ca` | Number of major vessels |
| `thal` | Thalassemia category |
| `target` | Heart disease outcome |

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- Jupyter Notebook
- Visual Studio Code

## Project Structure

```text
Heart_Health_Analysis/
│
├── heart.csv
├── heart_health_analysis.py
├── EDA Health Analysis.ipynb
├── requirements.txt
├── README.md
└── outputs/

Data
 ↓
Data Cleaning
 ↓
Feature Selection
 ↓
Train/Test Split
 ↓
Standardization
 ↓
Logistic Regression
 ↓
Prediction
 ↓
Model Evaluation
