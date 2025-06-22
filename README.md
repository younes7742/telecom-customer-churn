# 📊 Customer Churn Analysis and Prediction

This project focuses on analyzing customer data from a telecommunications company and building a machine learning model to predict customer churn.

---

## 🧠 Project Overview

The goal of this project is to:
- Explore and clean customer data
- Perform visual and statistical analysis
- Study the factors affecting customer churn
- Build a predictive model that identifies customers at risk of leaving
- Save the trained model for future deployment

---

## 🔍 Workflow Steps

1. **Data Merging**  
   Combined three separate tables into one unified dataset for analysis.

2. **Data Cleaning**  
   - Identified and corrected errors in each individual table.  
   - Checked for missing values, duplicates, and inconsistent formats.

3. **Exploratory Data Analysis (EDA)**  
   - Performed individual analysis for each table.  
   - Created various visualizations to understand customer behavior and trends.  
   - Analyzed relationships between features and the churn variable.

4. **Feature Engineering**  
   - Converted categorical variables to numerical using encoding techniques.

5. **Model Building**  
   - Built a classification model to predict customer churn.  
   - Evaluated model performance using metrics such as accuracy, precision, recall, and F1-score.

6. **Model Saving**  
   - Saved the trained model using `joblib` or `pickle` for reuse in other environments.

---

## 📁 Project Structure

```bash
churn-data-analysis/
│
├── data/               # Raw and cleaned datasets
├── notebooks/          # Jupyter notebooks for analysis and modeling
├── models/             # Saved machine learning models
├── images/             # Visualizations and plots
├── README.md           # Project overview and documentation
└── requirements.txt    # List of required Python libraries
