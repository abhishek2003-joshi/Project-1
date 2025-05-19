# E-commerce Return Rate Reduction Analysis

## 📌 Objective
The primary goal of this project is to understand the reasons behind product returns in an e-commerce setting. We aim to analyze how return rates vary across product categories, geographies, and marketing channels, and ultimately develop predictive insights to help reduce future returns.

## 🛠 Tools & Technologies
- **Python**: Data cleaning, analysis, and modeling
- **Power BI**: Interactive dashboard and visualization
- **SQL**: Data extraction and manipulation

## 📊 Project Workflow

### 1. Data Cleaning
- Cleaned and preprocessed the return and order datasets
- Handled missing values, outliers, and inconsistent formats

### 2. Exploratory Data Analysis
- Analyzed return percentages across:
  - Product categories
  - Suppliers
  - Geographical locations
  - Marketing channels

### 3. Predictive Modeling
- Built a **logistic regression model** in Python to predict the **probability of a product being returned**
- Evaluated model performance using appropriate classification metrics (e.g., accuracy, precision, recall)

### 4. Dashboard Creation
- Developed a **Power BI dashboard** featuring:
  - Return rates by category, supplier, and region
  - Return risk score based on model predictions
  - Interactive filters for real-time insights

## 📈 Key Outcomes
- Identified high-risk return categories and regions
- Built a return risk scoring system to flag potential returns before shipping
- Provided actionable insights for improving customer satisfaction and reducing return-related losses

└── logistic_regression_model.ipynb

📁 dashboard/

└── return_risk_dashboard.pbix
