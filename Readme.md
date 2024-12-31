# 🌟 Machine Predictive Maintenance Classification: A Comprehensive Data Analysis Project

Welcome to this insightful data analysis project, where we delve deep into predictive maintenance to uncover patterns, trends, and actionable insights for optimizing machine performance and failure prevention.

---

## 🚀 Project Overview

This project explores a dataset from a predictive maintenance system, focusing on the following:

- **Dataset Exploration**: Understanding the structure, characteristics, and distributions.
- **Data Cleaning**: Handling missing values and detecting anomalies.
- **Exploratory Data Analysis (EDA)**: Univariate, bivariate, and multivariate analysis.
- **Hypothesis Testing**: Statistical analysis to validate assumptions.
- **Data Visualization**: Comprehensive visual insights into machine behavior.
- **Failure Analysis**: Identifying root causes of machine failures.
- **Predictive Insights**: Insights into machine failure conditions.

---

## 🔍 Key Features of the Analysis

### 📊 Data Overview

- **Dataset Shape**: 10,000 rows × 10 columns.
- **Key Variables**:
  - `Torque [Nm]`: Torque values applied to the machine.
  - `Rotational speed [rpm]`: Speed of rotation during operation.
  - `Air temperature [K]`: Ambient temperature near the machine.
  - `Tool wear [min]`: Wear and tear on the machine's tool.
  - `Target`: Machine failure status (1 for failure, 0 for non-failure).

### 🛠️ Data Cleaning

- Handled missing values using:
  - Mean imputation for numerical columns.
  - Mode imputation for categorical columns.
- Identified outliers using Z-scores and visualized with box plots.

---

### 📈 Exploratory Data Analysis

#### Univariate Analysis
- **Visuals**:
  - Histograms and KDE plots for each numerical feature.
- **Insights**:
  - Distribution patterns of machine behavior metrics.

#### Bivariate & Multivariate Analysis
- **Techniques**:
  - Correlation matrix heatmap.
  - Pair plots for feature relationships.

---

### 📊 Visualizations

- **Key Charts**:
  - **Box plots**: Highlighting outliers and feature spread.
  - **Scatter plots**: Relationships like torque vs rotational speed.
  - **Area plots**: Wear trends over time.
  - **Line charts**: Temporal machine behavior patterns.

---

## 🔬 Hypothesis Testing

- **T-Test**: Comparison of torque between failure and non-failure conditions.
- **ANOVA**: Rotational speed across product quality levels.
- **Chi-Square Test**: Dependency between product type and failure.

---

## 🌡️ Failure Analysis

### Root Causes of Failures
- High correlation with:
  - **Torque and rotational speed**.
  - **Air and process temperatures**.
  - **Tool wear duration**.

### Statistical & Visual Insights
- **Torque Distribution**: Clear separation for failure vs. non-failure cases.
- **Correlation Matrix**: High correlations between operational features and failures.
- **Temperature Analysis**: Failure tendencies increase with rising process temperatures.

---

### Outliers and Predictors
- **Outliers**:
  - Significant anomalies in `Rotational speed [rpm]`.
  - Minor outliers in `Torque [Nm]`.
- **Failure Predictors**:
  - High torque values.
  - Low rotational speeds.
  - High tool wear durations.

---

## 🛠️ Tools & Technologies

- **Programming**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scipy, Statsmodels
- **Platform**: Google Colab

---

## 📈 Future Scope

- Develop a predictive model to classify machine failures using insights from this analysis.
- Implement real-time anomaly detection using advanced machine learning techniques.

---

## 📩 Contact

For any inquiries or collaboration opportunities, drop me an email: `debnathtirtha391@gmail.com`.

---

✨ *"Uncovering patterns today to prevent failures tomorrow!"*
