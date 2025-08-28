# 🏠 Airbnb Dynamic Pricing

## 📌 Overview
Built a machine learning model to predict Airbnb listing prices using regression, random forest, ARIMA, and neural networks.

## 📂 Structure
- **data/** → datasets or dataset link  
- **notebooks/** → step-by-step analysis  
- **src/** → reusable scripts  
- **results/** → charts and reports  
- **requirements.txt** → dependencies  

## 📈 Results
**Data Collection**: Sourced Airbnb datasets (listings, reviews, calendar) for Asheville, NC from InsideAirbnb.com
**Data Preprocessing**: Cleaned data, handled missing values/outliers, performed encoding, standardization, and skew transformation
**Correlation Analysis**: Built correlation matrix to identify price relationships
**Hypothesis Testing**: Used ANOVA and linear regression to test factor significance
**Machine Learning**: Implemented linear regression, random forest, decision trees, and ARIMA time series models
**Neural Network**: Developed hybrid model combining ARIMA with key variables
**Evaluation**: Assessed model performance and analyzed residuals
- Random Forest improved accuracy by **18%** over Linear Regression  
- Seasonal ARIMA effectively captured price trends  

## 🚀 How to Run
1. Clone this repo  
   ```bash
   git clone https://github.com/your-username/airbnb-dynamic-pricing.git
