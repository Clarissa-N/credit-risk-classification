# credit-risk-classification

## Repository Structure

**Credit_Risk:**
  - **credit_risk_classification:** File with code for the Logistic Regression Model.

  - **Resources:**

      - **lending_data:** Necessary CSV file


## Results

  The purpose of this analysis is to assess the performance of a Logistic Regression model in predicting loan risk. The model is evaluated based on its ability to accurately calssify loans into two categories which are 0 (Healthy loans), and 1 (high-risk loans). In order to do this, this model uses the metrics accuracy, precision, and recall. These insights allow the company to decide to use the model for automating loan risk which can help minimize future financial risk.

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

**Accuracy:**

    - 0.99 meaning 99% of the predicitons were accurate.
    - This model is very accurate in making overall predictions.

**Precision (Healthy Loan - 0):**
    - 1.00 meaning 100% of predicted healthy loans were actually healthy.
    - The model is perfect for identifying healthy loans with no false positives.
 
**Precision (High-Risk Loan - 1):**
    - 0.84 meaning 84% of predicted high-risk loans were actually high-risk.
    - Some false positives are present, but the model still preforms reasonably well at identifying high-risk loans.
 
**Recall (Healthy Loan - 0):**
    - 0.99 meaning 99% of actually healthy loans were predicted correctly.
    - The model misses very few healthy loans.

**Recall (High-Risk Loan - 1):**
    - 0.94 meaning 94% of actual high-risk loans were correctly predicted.
    - The model identifies most high-risk loans but misses some.

## Summary

  Overall, the Logistic Regression model is performing very well with 99% accuracy meaning the large majority of loan cases are being predicted correctly. When predicting healthy loans, the model predicts extremely well showing basically perfect precision and recall. As for high-risk loans, the model doesn't preform as well as there are some false positives, but overall still predicts reasonably well. The f1-scores for both are stong which indicates a good balance of precision and recall.

  Given the high overall accuracy and the models' ability to predict healthy loans nearly perfectly and high-risk loans reasonably well, I would reccomend this model for use by the company. The high scores produced by this model will allow for the company to minimize financial risk by preventing risky loans from being permitted. There should be some caution concerning the slightly lower precision score of the high-risk loan predicions which might allow for over-predicting high-risk loans. However, if the company is not concerned with a couple unnecessary rejections, this model would be useful in minimizing loss by correctly identifying most high-risk loans.
