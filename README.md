## Credit-Risk-class
- This analysis evaluates a logistic regression model for predicting credit risk. The dataset includes financial details like loan size, interest rate, borrower income, and debt-to-income ratio. The goal is to classify loans as high-risk or healthy.
# The process involved:
1.	Data Preparation: Cleaning and handling missing values.
2.	Data Splitting: Separating data into training and testing sets.
3.	Model Training: Training the logistic regression model.
4.	Model Evaluation: Assessing performance with accuracy, precision, and recall.

- The logistic regression model achieves a high overall accuracy of 99%, excelling in predicting healthy loans with a precision of 1.00 and a recall of 0.99. While it performs well in identifying high-risk loans, it has a slightly lower precision of 0.86 and a recall of 0.94, occasionally misclassifying high-risk loans as healthy. Despite this, the model effectively balances accuracy and risk prediction, making it a strong choice for credit risk assessment.

## **Logistic Regression Model:**
    * **Accuracy Score:** 99%
    * **Precision Score:**
        * `0` (healthy loan): 1.00
        * `1` (high-risk loan): 0.86
    * **Recall Score:**
        * `0` (healthy loan): 0.99
        * `1` (high-risk loan): 0.94


