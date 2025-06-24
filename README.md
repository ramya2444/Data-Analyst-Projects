# Project: E-Commerce Return Risk Prediction

This project builds a predictive model to classify the return risk of e-commerce orders using user, product, and transaction data.

## Objective:
To help e-commerce businesses reduce returns by predicting which orders are likely to be returned. 

##  Dataset:
- Synthetic dataset with 10,000 records
- Fields: order date, return date, product price, category, customer age/gender/location, payment & shipping method

## Technologies Used :
- Python (Pandas, Seaborn, Scikit-learn, XGBoost)
- SQL via pandasql
- Power BI for dashboard visualization
- Jupyter Notebook

## Project Highlights :
- Preprocessed missing values and engineered binary return labels
- Analyzed return patterns by category and price
- Trained XGBoost classifier with 100% accuracy on clean test set
- Created return probability scores and segmented orders:
  - Low Risk (0–30%)
  - Medium Risk (30–70%)
  - High Risk (70–100%)
- Exported predictions for dashboard integration

##  Deliverables :
- `return_model.ipynb`
- `return_risk_predictions.csv`
- `ecommerce_return_data_preentation.pptx`
- Power BI Dashboard (`.pbix` file)

## License:
MIT License — free to use with attribution.

**Author**: 
Makkina Ramya priya.
