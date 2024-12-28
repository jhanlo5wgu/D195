# D195 - Capstone Project - Justin Hanlon  ID 001267896 
## Project Title: Customer Satisfaction and Delivery Sensitivity in Brazilian E-Commerce
### Overview
This project analyzes delivery performance and its impact on customer satisfaction using data from the Brazilian e-commerce dataset. The analysis employs statistical and machine learning methods, including ANOVA and logistic regression, to draw actionable insights about the factors influencing customer satisfaction.

## Features
### Statistical Analysis:
ANOVA to test variances in satisfaction across distance and delay categories.
### Predictive Modeling:
Logistic regression to evaluate the impact of predictors like delivery delays and distance on customer satisfaction.
### Visualizations:
Charts illustrating insights (e.g., odds ratios, satisfaction trends) for stakeholder presentations.
## Repository Structure

/project-root  
├── ANOVA.ipynb            # Jupyter Notebook with all ANOVA analysis and outputs  
├── LogisticRegression.ipynb            # Jupyter Notebook with all Logistic Regression modeling and outputs  
├── data/  
│   └── olist_customers_dataset.csv           # Input customer data used in the analysis  
│   └── olist_geolocation_dataset.csv           # Input geolocation data used in the analysis  
│   └── olist_order_items_dataset.csv           # Input order items data used in the analysis  
│   └── olist_order_reviews_dataset.csv           # Input order review data used in the analysis  
│   └── olist_orders_dataset.csv           # Input order data used in the analysis  
│   └── olist_sellers_dataset.csv           # Input sellers data used in the analysis  
├── Data_Viz /  
│   └── olist_anova_combined_data.csv           # Output ANOVA data including no delay categories data used in the data visualization  
│   └── olist_anova_table.csv           # Output ANOVA data only minor and signigicant delay categories data used in the data visualization  
│   └── olist_logistic_table.csv           # Output Logistic Regression model odds ratios used in the data visualization  
├── requirements.txt          # Python libraries and dependencies  
├── README.md                 # Project documentation (this file)  

## Setup and Usage
### Prerequisites
Python 3.x
Jupyter Notebook or a compatible IDE  
### Installation
1. Clone the repository:
bash
git clone https://github.com/jhanlo5wgu/D195
cd jhanlo5wgu/D195

2. Install the required libraries
pip install -r requirements.txt

### Libraries Used
pandas – Data manipulation and analysis  
numpy – Numerical computations  
statsmodels – Statistical modeling (ANOVA, logistic regression insights)  
scikit-learn – Machine learning (logistic regression)  

## Contributors
Justin Hanlon
