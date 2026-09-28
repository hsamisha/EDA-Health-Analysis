# Heart Health Analysis - Exploratory Data Analysis

## Project Overview

Pulse of Prevention: Analyzing Heart Health for Better Outcomes is a Python-based data analysis project focused on exploring patient heart-health data and identifying patterns associated with the presence of heart disease.

The project performs data cleaning, exploratory data analysis, statistical analysis, visualization, feature preprocessing, and logistic regression modeling.

The analysis focuses on patient demographics, clinical measurements, chest pain, blood pressure, cholesterol, maximum heart rate, exercise-induced angina, and other clinical characteristics.

The goal is to transform healthcare data into meaningful analytical insights that can support further investigation of heart-disease-related patterns.

## Objective

The main objectives of this project are to:

- Analyze patient demographics and clinical characteristics.
- Understand the distribution of heart disease outcomes.
- Compare patients with and without heart disease.
- Analyze age, gender, blood pressure, cholesterol, and heart rate patterns.
- Examine different types of chest pain.
- Analyze exercise-induced angina and maximum heart rate.
- Investigate relationships between clinical variables and heart disease.
- Identify correlations between important features.
- Detect potential outliers in numerical variables.
- Normalize numerical features where required.
- Build a Logistic Regression model for heart disease classification.
- Evaluate the performance of the machine learning model.
- Generate clear and data-driven insights from the analysis.

## Dataset Description

The project uses the `heart.csv` dataset.

The dataset contains patient-level information related to cardiovascular health.

### Important Columns

| Column | Description |
|---|---|
| age | Age of the patient |
| sex | Sex of the patient |
| cp | Chest pain type |
| trestbps | Resting blood pressure in mm Hg |
| chol | Serum cholesterol level in mg/dl |
| fbs | Fasting blood sugar greater than 120 mg/dl |
| restecg | Resting electrocardiographic result |
| thalach | Maximum heart rate achieved |
| exang | Exercise-induced angina |
| oldpeak | ST depression induced by exercise |
| slope | Slope of the peak exercise ST segment |
| ca | Number of major vessels colored by fluoroscopy |
| thal | Thalassemia category |
| target | Presence or absence of heart disease |

The `target` variable represents the outcome:

- `1` = Heart disease present
- `0` = Heart disease absent

## Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- Jupyter Notebook
- Visual Studio Code
- CSV Dataset

## Approach / Methodology

The project follows a structured data-analysis workflow.

### 1. Data Collection

The `heart.csv` dataset was loaded into Python using Pandas.

### 2. Data Understanding

The dataset was examined to understand:

- Number of rows and columns
- Data types
- Feature descriptions
- Target variable
- Basic statistical information

### 3. Data Cleaning

The dataset was checked for:

- Missing values
- Duplicate records
- Incorrect data types
- Inconsistent values
- Potential data-quality issues

### 4. Exploratory Data Analysis

Exploratory analysis was performed on:

- Age distribution
- Gender distribution
- Heart disease distribution
- Chest pain types
- Resting blood pressure
- Cholesterol levels
- Maximum heart rate
- Exercise-induced angina
- Fasting blood sugar
- Resting ECG results
- Major vessels
- Thalassemia
- Other clinical measurements

### 5. Statistical Analysis

Statistical techniques were used to investigate relationships between important variables.

The analysis includes:

- Descriptive statistics
- Correlation analysis
- Group comparisons
- Distribution analysis
- Relationship analysis between clinical variables and the target variable

### 6. Outlier Detection

Numerical variables were examined for potential outliers using appropriate statistical and visualization techniques.

### 7. Feature Preprocessing

Numerical features were normalized or standardized where required for machine learning.

### 8. Machine Learning

A Logistic Regression model was developed to classify whether heart disease is present based on the available features.

The workflow includes:

- Feature selection
- Train-test split
- Feature standardization
- Logistic Regression
- Prediction
- Model evaluation

### 9. Visualization

Charts and plots were created using Matplotlib and Seaborn to communicate distributions, comparisons, correlations, and relationships between variables.

## Analysis & Key Findings

The analysis investigates the following major areas:

### Patient Demographics

Patient age and gender distributions were analyzed to understand the composition of the dataset.

### Clinical Measurements

Important clinical measurements such as:

- Resting blood pressure
- Cholesterol
- Maximum heart rate
- ST depression
- Number of major vessels

were analyzed to understand their distributions and relationship with the target outcome.

### Chest Pain Analysis

Different chest pain categories were examined and compared with the heart disease outcome.

This helps identify differences in heart-disease occurrence across chest pain groups.

### Exercise-Induced Angina

Exercise-induced angina was analyzed in relation to heart disease and maximum heart rate.

### Correlation Analysis

A correlation analysis was performed to identify relationships between numerical variables and the heart disease target.

The correlation results help identify variables that may warrant further investigation.

### Heart Disease Comparison

Patients with and without heart disease were compared across important clinical measurements to identify differences in their characteristics.

### Machine Learning Analysis

Logistic Regression was used as a classification model to investigate whether the available patient characteristics can be used to predict the presence of heart disease.

The model was evaluated using appropriate classification metrics.

## Key Insights

The final notebook cell contains the key insights generated directly from the completed exploratory analysis.

The insights summarize:

- Important patient characteristics
- Differences between target groups
- Major clinical patterns
- Strong relationships between variables
- Relevant risk-factor patterns
- Important observations from visualizations
- Machine-learning model performance

These insights should be interpreted as observations from the dataset and should not be treated as medical conclusions or clinical recommendations.

## Dashboard Overview

This project is primarily an Exploratory Data Analysis and Machine Learning project and does not contain a separate Tableau or Looker Studio dashboard.

The main analytical outputs are presented through Python visualizations and the Jupyter Notebook.

The notebook contains visual analysis such as:

- Distribution plots
- Count plots
- Box plots
- Histograms
- Correlation heatmaps
- Comparative visualizations
- Feature relationship plots
- Model evaluation outputs

## Recommendations

Based on the analytical areas explored in the project, the following actions can be considered for further analysis:

- Investigate variables that show stronger relationships with the heart disease target.
- Compare patient groups across multiple clinical measurements rather than relying on a single variable.
- Further investigate combinations of clinical factors associated with different target outcomes.
- Use additional and larger datasets to validate observed patterns.
- Evaluate multiple machine-learning algorithms for comparison.
- Perform feature-importance analysis to better understand model behavior.
- Validate analytical findings with qualified healthcare professionals before using them for clinical purposes.
- Continue monitoring model performance when new data becomes available.

## Conclusion

The Heart Health Analysis project demonstrates the practical application of Python-based data analysis techniques to a healthcare dataset.

The project covers data preparation, exploratory data analysis, statistical analysis, visualization, feature preprocessing, and Logistic Regression modeling.

The analysis provides a structured approach to understanding patient characteristics and identifying patterns associated with heart disease within the dataset.

This project demonstrates practical skills in:

- Data Cleaning
- Exploratory Data Analysis
- Statistical Analysis
- Data Visualization
- Feature Preprocessing
- Machine Learning
- Model Evaluation
- Data-driven Insight Generation

The results provide a foundation for further analysis and model development using larger and more diverse healthcare datasets.

# Key Insights

Based on the exploratory data analysis performed on the heart-health dataset, the following key insights were identified:

- The dataset contains patient demographic and clinical information that can be used to analyze patterns associated with heart disease.
- Patient age and gender distributions provide an overview of the population represented in the dataset.
- Different chest pain categories show differences in their distribution across heart disease outcomes.
- Clinical variables such as resting blood pressure, cholesterol, maximum heart rate, and ST depression were examined to identify differences between patients with and without heart disease.
- Exercise-induced angina was analyzed in relation to heart disease and maximum heart rate.
- Correlation analysis was performed to identify relationships between numerical variables and the heart disease outcome.
- The number of major vessels and thalassemia categories were also examined in relation to the target variable.
- Comparing patients with and without heart disease helps identify patterns that may be useful for further investigation.
- Logistic Regression was implemented as a classification model to evaluate whether the available features can be used to predict the target outcome.
- The findings from this analysis are specific to the dataset and should not be interpreted as medical conclusions.
