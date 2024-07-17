# Credit Card Churn Analysis

## Project Overview
This project involves the analysis of a dataset related to credit card churn. The goal is to identify key factors that contribute to customer churn and derive actionable insights to help the business retain customers.

## Dataset Description
The dataset contains various features related to credit card usage and customer demographics, including:

- Customer ID
- Age
- Gender
- Marital Status
- Income
- Education
- Occupation
- Number of Dependents
- Tenure with the bank
- Average monthly spend
- Number of products held
- Credit limit
- Balance
- Number of transactions
- Churn status (whether the customer has churned)

## Data Cleaning Procedures
1. **Handling Missing Values**: 
   - Identified and imputed missing values to maintain data integrity.

2. **Data Type Conversion**: 
   - Ensured all columns have appropriate data types for analysis.

3. **Outlier Detection and Treatment**:
   - Detected and managed outliers to prevent skewed analysis results.

4. **Encoding Categorical Variables**:
   - Encoded categorical variables to numerical values for better model performance.

5. **Normalization**:
   - Normalized numerical features to ensure uniform scale across the dataset.

## Key Insights

1. **Age and Churn**:
   - Younger customers (age 20-35) have a higher churn rate compared to older customers. This trend suggests that younger customers may have different banking needs or less loyalty to the bank.

2. **Income and Churn**:
   - Customers with lower income levels (< $50,000 annually) tend to churn more frequently. This might indicate that financial stability is a crucial factor in customer retention.

3. **Credit Limit and Churn**:
   - Customers with higher credit limits show lower churn rates. Higher credit limits might indicate a better relationship with the bank or higher satisfaction levels.

4. **Product Holding and Churn**:
   - Customers holding more banking products (e.g., loans, insurance) are less likely to churn. This highlights the importance of cross-selling to enhance customer loyalty.

5. **Marital Status and Churn**:
   - Single customers exhibit a higher churn rate compared to married customers. This could be due to varying financial responsibilities and lifestyle differences.

6. **Tenure and Churn**:
   - Longer tenure with the bank correlates with lower churn rates. This suggests that building long-term relationships is beneficial for customer retention.

## Conclusion
The analysis provides critical insights into the factors influencing credit card churn. By understanding these key drivers, the bank can implement targeted strategies to enhance customer retention, such as offering personalized products to younger and lower-income customers, increasing cross-selling efforts, and improving credit limits for high-risk customers.

## File Included
- `Credit_Card_CHURN.ipynb`: Jupyter Notebook containing the data analysis and visualizations.



## How to Run the Analysis
1. Clone this repository to your local machine.
2. Ensure you have Jupyter Notebook installed.
3. Open the Jupyter Notebook file (`Credit_Card_CHURN (1).ipynb`) and run the cells to reproduce the analysis.

## Contact
For any questions or suggestions, feel free to contact me at tobilobapeculiar@gmail.com
