# E-Commerce Customer Analysis  

This repository contains an exploratory data analysis (EDA) and predictive modeling project on an **E-Commerce dataset**. The goal is to understand customer behavior and predict future spending patterns based on available features.  

## 📂 Repository Contents
- **E_Commerce.ipynb** – Jupyter Notebook with complete analysis, visualizations, and model building.  
- **Ecommerce Customers** – Dataset used in the analysis (CSV file).  
- **requirements.txt** – List of dependencies to run the notebook.  

## 📊 Project Overview
The dataset contains information about customers such as:
- Email, Address, and Avatar  
- Average Session Length  
- Time on App  
- Time on Website  
- Length of Membership  
- Yearly Amount Spent (Target Variable)  

### Key Steps:
1. **Data Cleaning & Exploration**  
   - Inspect dataset  
   - Check for missing values and outliers  
   - Visualize relationships between variables  

2. **Exploratory Data Analysis (EDA)**  
   - Correlation analysis  
   - Pairplots & heatmaps  
   - Distribution of key features  

3. **Modeling**  
   - Linear Regression model to predict yearly customer spending  
   - Evaluation with RMSE, R²  

4. **Insights**  
   - Comparison of **App usage vs Website usage**  
   - Feature importance in predicting customer value  

## 🚀 Installation & Setup
To run this project locally:  

```bash
# Clone the repository
git clone https://github.com/your-username/e-commerce-customer-analysis.git

# Navigate into the repo
cd e-commerce-customer-analysis

# Install dependencies
pip install -r requirements.txt
```

## 🛠 Requirements

Python 3.x

pandas

numpy

matplotlib

seaborn

scikit-learn

jupyter

Install all requirements with:
```bash
pip install -r requirements.txt
```

## 📈 Results

-Length of Membership is the strongest predictor of yearly customer spending.

-Time on App has a higher impact than Time on Website.

-The model achieved good accuracy with linear regression, showing strong correlation between predicted and actual spending.

## 📌 Future Improvements

-Experiment with advanced models (Random Forest, Gradient Boosting).

-Deploy as a web app for interactive predictions.

-Incorporate more customer demographic data if available.
