# Internship Project Portfolio – Data Analytics

This repository contains two machine learning and data analysis projects completed during my internship. Both projects are based on real-world business problems and leverage Python, SQL, and visualization tools to produce predictive models and actionable insights.

---

##  Table of Contents
- [ Project 1: Telecom Customer Churn Analysis](#project-1-telecom-customer-churn-analysis)
- [ Project 2: E-Commerce Return Risk Prediction](#project-2-e-commerce-return-risk-prediction)
- [ Technologies Used](#technologies-used)
- [ License](#license)
- [ Author](#author)

---

##  Project 1: Telecom Customer Churn Analysis

**Objective**:  
To build a predictive model that identifies telecom customers at risk of churning and to recommend strategies for retention.

### Dataset :
- 3,333 customer records
- Fields: call durations, plan subscriptions, charges, service complaints, churn status

###  Project Highlights :
- Data cleaning and feature engineering: `total_calls`, `total_minutes`, `total_charges`
- Exploratory Data Analysis (EDA) to identify churn influencers
- Model: Random Forest Classifier (97.45% accuracy)
- Used `ELI5` to interpret top churn predictors
- Segmentation:
  - **At Risk** (churn_prob > 0.7)
  - **Neutral** (0.3–0.7)
  - **Loyal** (< 0.3)
- Exported predictions for business use: `churn_segments.csv`

###  Deliverables :
- `Customer_telecom_churn.ipynb` – Jupyter notebook
- `Customer_telecom_ppt.pptx` – Presentation
- `Customer_Telecom_Churn_Report.pdf` – Final report
- `churn_segments.csv` – Output predictions

---

##  Project 2: E-Commerce Return Risk Prediction

**Objective**:  
To predict which e-commerce orders are likely to be returned, helping the business reduce costs and improve product strategy.

###  Dataset:
- 10,000 synthetic orders
- Fields: product price, quantity, category, customer age/gender/location, return label, payment/shipping method

###  Project Highlights:
- Cleaned and encoded dataset; filled missing values
- Created `Return_Status` target based on return date
- SQL insights: Return rate by product category using `pandasql`
- Model: XGBoost Classifier (100% accuracy on clean data)
- Added `Return_Probability` for each order
- Segmentation:
  - **Low Risk** (0–30%)
  - **Medium Risk** (30–70%)
  - **High Risk** (70–100%)
- Exported predictions for dashboard use (Power BI)

###  Deliverables:
- `ecommerce_return_model.ipynb` – Jupyter notebook
- `ecommerce_ppt.pptx` – Presentation
- `ecommerce_returns_synthetic_data_dashboard.pbix` – Power BI dashboard
- `return_risk_predictions.csv` – Model output

---

##  Technologies Used:

- **Languages & Libraries**: Python, SQL, Pandas, Seaborn, Scikit-learn, XGBoost, Matplotlib
- **ML Techniques**: Classification, Feature Importance, Model Explainability (ELI5)
- **Visualization Tools**: PowerPoint, Power BI
- **Tools**: Jupyter Notebook, pandasql, ELI5

---

##  License:

This repository is licensed under the **MIT License**.  
You are free to use, modify, and share this code with proper attribution.

---

##  Author

**Makkina Ramya Priya**  
Data Analytics Intern – 2025  
📧 ramyapriyamakkina@gmail.com  
🌐 [https://www.linkedin.com/in/makkinaramyapriya]
