# README.md

# Churn Analysis in Telecom Industry

Churn is a significant challenge in the telecom industry, with research indicating an average monthly churn rate of 1.9% - 2% among major wireless carriers in the US. This repository explores the problem of churn prediction using various machine learning techniques and extensive exploratory data analysis (EDA).

## Dataset

The analysis is performed on the Telecom Customer Churn dataset, which includes features like customer demographics, contract details, and services subscribed.

## Libraries Used

- **NumPy**: For numerical operations
- **Pandas**: For data manipulation and analysis
- **Seaborn and Matplotlib**: For data visualization
- **Scikit-Learn**: For machine learning models

## Steps Taken

1. **Data Cleaning and Preprocessing**:
    - Loaded the dataset and examined its structure.
    - Checked for missing values and handled them appropriately.
    - Converted categorical variables into numerical data using one-hot encoding.

2. **Exploratory Data Analysis (EDA)**:
    - Explored the relationships between various factors and customer churn.
    - Analyzed demographics, contract types, tenure, and services subscribed.
    - Visualized the data to identify patterns and correlations.
    
3. **Churn Prediction Models**:
    - **Logistic Regression**: Utilized logistic regression to predict churn and evaluated the accuracy.
    - **Random Forest**: Implemented a random forest classifier and identified the most significant features influencing churn.
    - **Support Vector Machine (SVM)**: Utilized SVM with a linear kernel and fine-tuned parameters to achieve higher accuracy.
    - **AdaBoost**: Applied AdaBoost classifier to enhance predictive accuracy.
    - **XGBoost**: Utilized XGBoost, a robust and scalable machine learning model, achieving an accuracy of nearly 83%.

## Key Findings

- **Contract Type Impact**: Month-to-month contracts show a high churn rate compared to one and two-year contracts.
- **Customer Tenure**: Longer tenure correlates with lower churn rates, indicating customer loyalty.
- **Monthly Charges and Services**: Higher monthly charges and specific services like fiber optic internet increase churn likelihood.
- **Predictive Accuracy**: XGBoost outperforms other models, achieving an accuracy of approximately 83%.

## Conclusion

The analysis demonstrates the complexity of customer churn in the telecom industry. Utilizing advanced machine learning models like XGBoost, companies can predict and mitigate churn effectively. Further research and feature engineering could enhance predictive accuracy, aiding telecom companies in customer retention strategies.

Feel free to explore the notebook for a detailed understanding of the analysis and predictive models!
