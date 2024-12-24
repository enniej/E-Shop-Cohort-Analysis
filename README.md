# E-Shop Cohort Analysis for Customer Retention
This repository conducts a cohort analysis for E-Shop Pro to address declining customer retention rates. By leveraging customer data, it identifies patterns in behaviour, retention, and churn. Using advanced analytics and machine learning, the project provides actionable insights to enhance customer loyalty and optimise business strategies.

![image](https://github.com/user-attachments/assets/47a27176-e6ce-4faa-a4c6-4e1942ab167c)


This project analyses customer retention patterns for E-Shop Pro using cohort analysis. It uses customer data to uncover trends, pinpoint churn behaviour, and identify strategies to enhance loyalty in the competitive e-commerce landscape. By employing advanced analytics and machine learning, the project delivers actionable insights to improve customer engagement and retention.

---

## Table of Contents
1. [Overview](#overview)
2. [Business Problem](#business-problem)
3. [Rationale for the Project](#rationale-for-the-project)
4. [Aim of the Project](#aim-of-the-project)
5. [Data Description](#data-description)
6. [Tech Stack](#tech-stack)
7. [Project Scope](#project-scope)
8. [Methodology](#methodology)
9. [Results](#results)
10. [Recommendations](#recommendations)
11. [Future Work](#future-work)
12. [Conclusion](#conclusion)

---

## 1. Overview
E-Shop Pro faces a critical challenge in retaining its customers. While the company has successfully attracted new customers, declining retention rates threaten profitability and long-term growth in the highly competitive e-commerce industry. This project leverages cohort analysis to understand customer retention patterns and devise data-driven strategies to address the issue.

---

## 2. Business Problem
Customer retention is crucial for the long-term sustainability of any e-commerce business. For E-Shop Pro:
- Declining retention rates reduce repeat business, impacting profitability.
- Vast amounts of customer data remain underutilised, leading to missed opportunities for understanding behaviour and preferences.

This project uses cohort analysis to understand and address these challenges.

---

## 3. Rationale for the Project
Cohort analysis provides deeper insights into customer behaviour over time, enabling E-Shop Pro to:
- **Identify Retention Trends**: Group customers based on acquisition date and track their behaviour over time.
- **Pinpoint Churn Patterns**: Understand when and why customers stop engaging or making purchases.
- **Optimise Retention Strategies**: Use insights to design interventions for improving loyalty and customer satisfaction.

---

## 4. Aim of the Project
The aim of this project is to:
- Gain comprehensive insights into customer engagement and retention through cohort analysis.
- Identify trends in retention and churn over time.
- Provide actionable recommendations to improve customer loyalty and business profitability.

---

## 5. Data Description
The dataset includes key features for customer behaviour and transaction analysis:
- **InvoiceNo**: Unique identifier for each transaction.
- **StockCode**: Product or item identifier.
- **Description**: Textual description of the product.
- **Quantity**: Number of units purchased.
- **InvoiceDate**: Date and time of the transaction.
- **UnitPrice**: Price per unit of the product.
- **CustomerID**: Unique identifier for each customer.
- **Country**: Country of the customer.

---

## 6. Tech Stack
The project uses the following technologies and libraries:
- **Programming Language**: Python
- **Libraries**:
  - **NumPy**: Numerical operations
  - **Pandas**: Data manipulation and analysis
  - **Matplotlib** and **Seaborn**: Data visualisation
  - **Scikit-learn**: Machine learning

---

## 7. Project Scope
The scope of this project includes:
1. **Exploratory Data Analysis (EDA)**:
   - Explore and visualise data to identify patterns and trends in customer retention and behaviour.
   - Uncover anomalies and correlations in the dataset.

2. **Feature Engineering**:
   - Create meaningful features from existing data, such as cohort groups and retention metrics.
   - Transform and scale features to improve model performance.

3. **Model Development**:
   - Develop predictive models to identify factors influencing retention and churn.
   - Fine-tune models for optimal accuracy and interpretability.

4. **Model Evaluation and Selection**:
   - Evaluate models using performance metrics like accuracy, precision, recall, and F1-score.
   - Select the best-performing model(s) for actionable insights.

---

## 8. Methodology
### Step 1: Data Preprocessing
- Handle missing values and duplicates.
- Convert transaction dates to datetime format for temporal analysis.
- Group customers into cohorts based on acquisition date.

### Step 2: Exploratory Data Analysis (EDA)
- Analyse cohort retention rates over time.
- Identify trends in churn and customer behaviour.

### Step 3: Feature Engineering
- Create cohort-based metrics such as retention rates, churn rates, and lifetime value (LTV).

### Step 4: Model Development
- Apply machine learning models to predict customer churn likelihood.
- Train models like logistic regression, decision trees, and random forests.

### Step 5: Evaluation
- Use metrics such as AUC-ROC, accuracy, and recall to evaluate model performance.
- Select the most reliable model for predicting churn.

---

## 9. Results
Key findings include:
- Retention rates decline sharply within the first few months of customer acquisition.
- Customers who make repeat purchases within the first month are more likely to remain loyal.
- Specific products and countries exhibit higher churn rates.

---

## 10. Recommendations
To improve retention, E-Shop Pro should:
1. **Implement Personalised Retention Campaigns**:
   - Target at-risk customers with offers and personalised communication.
2. **Optimise Onboarding Experiences**:
   - Provide incentives for repeat purchases within the first month.
3. **Enhance Product Offerings**:
   - Focus on high-churn product categories for improvements.

---

## 11. Future Work
Potential areas for further exploration include:
- Incorporating external factors such as marketing campaigns and seasonality into the analysis.
- Developing real-time dashboards for tracking retention metrics.
- Applying advanced machine learning techniques like gradient boosting for improved predictions.

---

## 12. Conclusion
This project provides a robust framework for analysing customer retention patterns and identifying strategies to enhance loyalty. By leveraging cohort analysis and machine learning, E-Shop Pro can address declining retention rates and strengthen its competitive position in the e-commerce industry.

---

