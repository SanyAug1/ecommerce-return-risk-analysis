# 🛒 E-Commerce Return Risk Analysis & Prediction
### End-to-End Data Analytics and Machine Learning Project using Python, Scikit-Learn & Power BI

## 📌 Project Overview

This project presents an end-to-end data analytics and machine learning solution for analyzing product return behavior in an e-commerce business. The objective is to identify the factors influencing product returns, uncover business insights through exploratory data analysis, build predictive machine learning models, and develop an interactive Power BI dashboard for decision-making.

The project follows the complete data analytics lifecycle, including data preprocessing, visualization, predictive modeling, and business intelligence reporting.

---

# 🎯 Objectives

- Analyze customer return behavior using historical e-commerce transaction data.
- Identify product categories with the highest return rates.
- Compare return trends across different regions and payment methods.
- Understand the major reasons behind product returns.
- Study the impact of discounts, shipping costs, and profit margins on returns.
- Build machine learning models to predict product return risk.
- Design an interactive Power BI dashboard for business users.

---

# 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook
- Power BI

---

# 📂 Dataset

The dataset contains approximately **35,000 e-commerce transactions** with information such as:

- Order ID
- Customer Details
- Product Category
- Product Price
- Quantity
- Region
- Payment Method
- Shipping Cost
- Discount
- Profit Margin
- Order Date
- Delivery Date
- Return Status
- Return Reason

---

# 🧹 Data Cleaning & Preprocessing

The following preprocessing steps were performed:

- Removed duplicate records
- Checked and handled missing values
- Converted date columns into datetime format
- Created additional date features (Month, Quarter, Year, Delivery Days)
- Encoded categorical variables using One-Hot Encoding
- Prepared the dataset for machine learning

---

# 📊 Exploratory Data Analysis (EDA)

Several visualizations were created to understand customer return patterns and business performance.

### Analysis Performed

- Return Distribution
- Return Rate by Product Category
- Return Rate by Region
- Return Rate by Payment Method
- Return Reasons Analysis
- Discount vs Return Analysis
- Profit Margin Distribution
- Average Profit Margin by Category
- Shipping Cost Analysis
- Average Shipping Cost by Region
- Customer Age Distribution
- Customer Gender Analysis

---

# 🤖 Machine Learning

The project includes predictive modeling to identify whether an order is likely to be returned.

### Logistic Regression

- Developed a baseline Logistic Regression model.
- Initial Accuracy: **94.48%**
- Evaluated model performance on an imbalanced dataset.
- Implemented a balanced Logistic Regression model to improve prediction of returned orders.

### Random Forest Classifier

A Random Forest Classifier was developed to improve prediction performance.

**Model Performance**

- Accuracy: **94.12%**

Feature Importance analysis identified the strongest predictors of product returns.

Top important features include:

- Profit Margin
- Shipping Cost
- Product Price
- Customer Age
- Discount

---

# 📈 Business Insights

Key findings from the analysis include:

- Fashion products have the highest return rate among all categories.
- Electronics generate the highest average profit margin.
- The East region records the highest return percentage.
- "Not as Described" is the most common reason for product returns.
- Profit Margin, Shipping Cost, Product Price, Customer Age, and Discount are the most influential variables affecting return prediction.

---

# 📊 Power BI Dashboard

An interactive Power BI dashboard was created to visualize business performance and return behavior.

### Dashboard KPIs

- Total Orders
- Total Revenue
- Total Returns
- Return Rate (%)
- Average Profit Margin
- Average Shipping Cost

### Interactive Filters

- Product Category
- Region
- Payment Method
- Return Status

### Dashboard Visualizations

- Return Rate by Category
- Return Rate by Region
- Total Returns by Return Reason
- Average Profit Margin by Category

The dashboard enables users to interactively explore trends and gain actionable business insights.

---

# 📷 Dashboard Preview

*(Upload your dashboard screenshot and replace the line below with the image.)*

```markdown
![Dashboard](dashboard.png)
```

---

# 📄 Repository Files

This repository contains:

- Kaggle_Ecommerce_Data.csv
- ecommerce_return_analysis.ipynb
- ecommerce_return_dashboard.pbix
- high_risk_products.csv
- requirements.txt
- README.md

---

# 🚀 Future Improvements

Potential enhancements for this project include:

- Hyperparameter Tuning
- XGBoost Classifier
- LightGBM Model
- SHAP Explainability
- Streamlit Dashboard Deployment
- Real-Time Prediction System
- Model Deployment using Flask or FastAPI

---

# 🎓 Key Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Engineering
- Machine Learning
- Classification Models
- Business Intelligence
- Power BI Dashboard Development
- Business Insight Generation

---

# 👨‍💻 Author

**Sanay Mishra**

Aspiring Data Analyst

## Skills

- Python
- SQL
- Excel
- Power BI
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
