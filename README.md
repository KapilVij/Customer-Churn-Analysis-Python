# Telecom-Customer-Churn-Analysis-Python-Project

## Overview
This project analyzes customer churn in a telecom company using various visualizations and a linear regression model. The goal is to identify key factors influencing churn and provide actionable business insights to improve customer retention.

## Dataset
The dataset consists of customer details, contract information, payment methods, tenure, monthly charges, and churn status. The primary objective is to understand patterns and predict customer churn effectively.

## Python Libraries Used in This Project
**Data Handling & Analysis**

- pandas – For data manipulation and analysis.
- numpy – For numerical computations.

**Data Visualization**
- matplotlib – For creating static visualizations.
- seaborn – For enhanced statistical visualizations.

**Machine Learning & Model Building**
- scikit-learn (sklearn) – For building the Linear Regression model, evaluation, and splitting data.
- LinearRegression – To build the regression model.
- train_test_split – To split the dataset into training and testing sets.
- accuracy_score, classification_report – To evaluate the model.

---

## Visualizations and Insights

### 1. Churn Distribution
![Image](https://github.com/user-attachments/assets/f9cedbb3-8485-4d70-82b6-3d6434de6abc)

**Description:** This visualization presents the overall distribution of churned vs. retained customers.

- **Observation:** A significant portion of customers have churned, indicating a need for better retention strategies.

### 2. Churn by Contract Type
![Image](https://github.com/user-attachments/assets/5e83eb35-e056-4e70-b757-87747e14bf1a)

**Description:** This chart displays the churn rate based on different contract types (Month-to-Month, One Year, Two Years).

- **Observation:** Customers with month-to-month contracts have the highest churn rate, whereas those with longer contracts (one year or two years) show significantly lower churn.
- **Business Recommendation:** Encouraging long-term contracts through discounts and loyalty benefits can help reduce churn.

### 3. Churn by Internet Service Type
![Image](https://github.com/user-attachments/assets/39b237b9-aa11-46e3-b724-c843bae9d283)
**Description:** This visualization examines churn rates across different internet service types (Fiber Optic, DSL, No Internet Service).

- **Observation:** Customers using Fiber Optic internet have a higher churn rate compared to DSL users.
- **Business Recommendation:** Improve service reliability for Fiber Optic customers or offer bundled services to increase retention.

### 4. Churn by Payment Method
![Image](https://github.com/user-attachments/assets/f02832a1-b37b-4aa8-9682-da37e0922bda)

**Description:** This analysis explores how different payment methods affect churn.

- **Observation:** Customers using Electronic Check payment method exhibit the highest churn rate, whereas those using automatic bank payments or credit cards have lower churn rates.
- **Business Recommendation:** Encourage customers to switch to automatic payments through incentives like discounts or rewards.

### 5. Monthly Charges vs. Churn
![Image](https://github.com/user-attachments/assets/eb503fe2-908f-4c2b-9401-42d636e2fe72)
**Description:** This scatter plot visualizes the relationship between monthly charges and churn.

- **Observation:** Higher monthly charges correlate with increased churn.
- **Business Recommendation:** Offering customized pricing plans or loyalty discounts can help retain high-paying customers.

### 6. Tenure vs. Churn
![Image](https://github.com/user-attachments/assets/7ed42aab-f2ed-4ed4-9db3-85172e20acf1)

**Description:** This plot analyzes how customer tenure (length of service) affects churn.

- **Observation:** Customers with shorter tenure are more likely to churn.
- **Business Recommendation:** Implementing onboarding programs and early-stage customer engagement strategies can help improve retention.

---

## Linear Regression Model
A linear regression model was used to analyze the relationship between customer tenure, monthly charges, contract type, payment method, and churn likelihood.

### Model Performance Metrics:

- **Accuracy:** 0.8261 (82.61%)
- **Precision, Recall, and F1-score:**

```
              precision    recall  f1-score   support

          No       0.86      0.91      0.88      1036
         Yes       0.70      0.60      0.64       373

    accuracy                           0.83      1409
   macro avg       0.78      0.75      0.76      1409
weighted avg       0.82      0.83      0.82      1409
```

### Interpretation:
- The model correctly predicts churn with **82.61% accuracy**.
- The **precision for "Yes" (churned customers) is 70%**, meaning 70% of predicted churn cases were actual churn.
- The **recall for "Yes" (churned customers) is 60%**, indicating that 60% of actual churn cases were identified by the model.
- The weighted F1-score is **0.82**, which shows a good balance between precision and recall.

---

## Key Business Recommendations
1. **Encourage Long-Term Contracts:** Reduce churn by offering discounts for annual and bi-annual contracts.
2. **Improve Fiber Optic Service Reliability:** Address pain points leading to higher churn in Fiber Optic users.
3. **Promote Auto-Payments:** Reduce churn by incentivizing bank transfers and credit card auto-payments.
4. **Customize Pricing for High-Spending Customers:** Offer tailored loyalty programs or discounts.
5. **Enhance Early Customer Engagement:** Implement strong onboarding programs to retain new customers.

---

## Conclusion
This project also demonstrates how Linear Regression can analyze customer churn trends and this project also analysis and highlights key drivers of customer churn and provides actionable insights to improve retention. By implementing the suggested strategies, telecom companies can reduce churn and enhance customer loyalty effectively. 

---

## Thank You

