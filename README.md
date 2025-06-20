# 🛒 Big Mart Sales Prediction

This project builds a regression model to predict the sales of products across various Big Mart outlets using historical data. The goal is to help the retail chain optimize inventory management and improve overall profitability.

## 📌 Problem Statement

Big Mart is a large retail chain that wants to leverage historical sales data across its stores to predict future sales for various products. This project uses machine learning techniques to forecast sales based on product and store-related features.

## 📂 Dataset

The dataset contains information on:
- Product ID, weight, category, MRP
- Store ID, size, location type, establishment year
- Sales figures (target variable)

**Target Variable:** `Item_Outlet_Sales` – sales of a product at a particular store.

## 🔍 Steps Performed

1. **Data Loading & Cleaning**
   - Handling missing values and inconsistencies
   - Standardizing categorical data

2. **Exploratory Data Analysis (EDA)**
   - Understanding feature distributions
   - Analyzing relationships between variables

3. **Feature Engineering**
   - Encoding categorical variables using LabelEncoder

4. **Model Building**
   - Random Forest Regressor
   - Gradient Boosting Regressor
   - Evaluation using RMSE and R² score

5. **Feature Importance**
   - Visualizing key drivers of sales predictions

## 📈 Model Evaluation Metrics

- **R² Score**: Measures goodness of fit
- **RMSE**: Measures average prediction error in the same unit as the target

## 📁 Files

- `BigMart_Sales_Prediction_Model.ipynb`: Jupyter Notebook with full analysis and model.
- `Supermarket_sales_prediction.csv`: Input dataset (not included due to size/licensing).
- `README.md`: This project description.

## ✅ Requirements

- Python 3.x
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

Install requirements using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
