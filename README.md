# IBM Telco SaaS Customer Churn Prediction & Retention Strategy

This project simulates a **real-world product analytics** scenario: predicting customer churn for a SaaS company and testing retention strategies using A/B testing.

## Project Objective

- Identify **factors driving customer churn**
- Build a **predictive model** to flag at-risk customers
- Simulate an **A/B test** to measure impact of retention offers

##  Dataset

- **Source:** IBM Telco Customer Churn dataset
- **Rows:** 7,043 customers
- **Features:** 21 (contract type, charges, services, demographics, etc.)
- **Target:** `Churn` (Yes/No)

## Tools & Techniques Used

- **Language:** Python (Jupyter Notebooks)
- **Libraries:** pandas, numpy, seaborn, matplotlib, scikit-learn, scipy
- **Techniques:** 
  - Exploratory Data Analysis (EDA)
  - Feature Encoding
  - Logistic Regression & Random Forest Modeling
  - A/B Test Simulation with Statistical Significance Testing

##  Key Findings

### 🔹 **Model Insights**
- Logistic Regression: **Accuracy 81.6%**, ROC-AUC 0.859
- Random Forest: **Accuracy 79.5%**, ROC-AUC 0.843
- Top churn drivers: **Tenure**, **Contract Type**, **Monthly Charges**, **Online Security**

### 🔹 **A/B Test Results**
- Control Retention: **73.9%**
- Treatment Retention: **78.5%**
- **Retention Lift:** +4.6%
- **p-value:** 0.018 (statistically significant)

## Recommendations

- Focus retention campaigns on **short-tenure** customers
- Offer **targeted discounts** for **month-to-month** plans
- Enhance **online security** features to improve retention
- Deploy predictive models to monitor churn proactively

## Files Included

| File | Description |
|------|-------------|
| `notebooks/01_eda_churn.ipynb` | Data cleaning, EDA |
| `notebooks/02_modeling_churn.ipynb` | Modeling + A/B test |
| `data/telco_churn.csv` | Dataset used |
| `report/KhushbooMasih_SaaS_ChurnPrediction_CaseStudy_Aug2025.pptx` | Final project presentation |

## Author

**Khushboo Masih**  
MSc Data Science  
📫 khushboomasih193@gmail.com  
🔗 [GitHub](https://github.com/Khush505)  
🔗 [LinkedIn](https://www.linkedin.com/in/khushboo-masih/)

## License

For educational and portfolio purposes only.
