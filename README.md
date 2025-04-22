# 📊 Telco Customer Churn Prediction

This project dives into customer churn behavior using the Telco Customer Churn dataset. It combines exploratory data analysis (EDA) and machine learning to identify patterns and build predictive models that can help telecom companies reduce customer attrition.

## 🔍 Key Insights:
- Customers with month-to-month contracts, fiber optic internet, and electronic check payments are more likely to churn.
- Shorter tenure, higher monthly charges, and lower total charges are common traits of churned customers.
- Senior citizens and those without dependents showed a higher churn rate.

## 🧠 Model Comparison:
| Model                | Accuracy |
|---------------------|----------|
| Logistic Regression | ~XX%     |
| Random Forest       | ~YY%     |

> Random Forest outperformed due to its robustness with feature interactions and categorical variables.

## 🔧 Top Features Influencing Churn:
- Tenure
- Monthly Charges
- Contract Type
- Internet Service
- Online Security

## 📦 Deliverables:
- `churn_analysis.ipynb`: Complete EDA + ML notebook
- `churn_rf_model.pkl`: Trained Random Forest model (optional)
- `final_dataset.csv`: Cleaned dataset with encoded features

## 📈 Business Recommendations:
- Encourage long-term contracts to reduce churn.
- Offer targeted promotions for high-risk customers (e.g., fiber optic users).
- Improve services or support for early-stage customers (low tenure).
