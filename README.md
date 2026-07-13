# 📊 Telco Customer Churn - Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the Telco Customer Churn dataset to understand customer behavior and identify factors influencing customer churn. The analysis includes data cleaning, preprocessing, statistical analysis, and visualizations to uncover meaningful business insights that can help improve customer retention.

---

## 🎯 Project Objectives

- Understand the dataset and its features.
- Clean and preprocess the data.
- Handle missing values and incorrect data types.
- Perform univariate, bivariate, and multivariate analysis.
- Identify patterns related to customer churn.
- Visualize important trends using Python libraries.
- Generate actionable business insights.

---

## 📂 Dataset Information

- **Dataset Name:** Telco Customer Churn
- **Source:** Kaggle
- **Records:** 7,043
- **Features:** 21
- **Target Variable:** Churn

### Dataset Features

- Customer Demographics
- Account Information
- Services Subscribed
- Billing Information
- Contract Details
- Customer Churn Status

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📋 Project Workflow

### 1. Data Loading
- Imported the dataset into Jupyter Notebook.

### 2. Data Cleaning
- Checked missing values.
- Removed duplicate records.
- Converted data types where necessary.
- Handled blank values in `TotalCharges`.
- Renamed columns (if required).

### 3. Exploratory Data Analysis
- Dataset overview
- Descriptive statistics
- Distribution analysis
- Correlation analysis
- Churn analysis
- Customer segmentation

### 4. Data Visualization
- Count Plots
- Histograms
- Box Plots
- Bar Charts
- Pie Charts
- Heatmap
- Pairwise Comparisons (if applicable)

---

## 📈 Key Insights

- Customers with month-to-month contracts are more likely to churn.
- Customers with higher monthly charges tend to have higher churn rates.
- Long-tenure customers are less likely to churn.
- Fiber optic internet users show relatively higher churn.
- Customers without online security or technical support are more likely to leave.
- Electronic check payment method is associated with higher churn.

---

## 📁 Project Structure

```
Telco-Customer-Churn-EDA/
│
├── dataset/
│   └── Telco-Customer-Churn.csv
│
├── notebooks/
│   └── Telco_Customer_Churn_EDA.ipynb
│
├── images/
│   ├── churn_distribution.png
│   ├── heatmap.png
│   ├── contract_analysis.png
│   └── monthly_charges.png
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

## ▶️ How to Run the Project

### Clone the repository

```bash
git clone https://github.com/your-username/Telco-Customer-Churn-EDA.git
```

### Navigate to the project directory

```bash
cd Telco-Customer-Churn-EDA
```

### Install the required libraries

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook and run all cells.

---

## 📷 Sample Visualizations

Include screenshots of:

- Customer Churn Distribution
- Correlation Heatmap
- Contract Type vs Churn
- Monthly Charges Distribution
- Tenure Analysis
- Payment Method Analysis

---

## 🚀 Future Improvements

- Build a machine learning model for churn prediction.
- Develop an interactive dashboard using Power BI or Tableau.
- Deploy the project using Streamlit.
- Perform feature engineering to improve predictive analysis.

---

## 📚 References

- Kaggle - Telco Customer Churn Dataset
- Pandas Documentation
- NumPy Documentation
- Matplotlib Documentation
- Seaborn Documentation

---

## 👨‍💻 Author

**Sai Kumar**

- LinkedIn:https://www.linkedin.com/in/tangadapallysaikumar/
- GitHub: https://github.com/Saikumar7076

---

⭐ If you found this project useful, consider giving it a star!
