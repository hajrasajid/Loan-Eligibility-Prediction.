**Loan Approval Prediction using Logistic Regression**

**Project Overview**

This project focuses on predicting loan approval status (Approved/Not Approved) using a Logistic Regression model. The objective is to build a reliable classification system that can assist in decision-making based on applicant information such as income, credit history, and demographic features.

A key challenge addressed in this project is class imbalance, which is handled using a balanced learning approach to ensure fair performance across both classes.

**Dataset Description**

The dataset contains 614 records with 13 features, including both numerical and categorical variables.

**Key attributes include**

- Applicant income and co-applicant income
- Loan amount and loan term
- Credit history
- Demographic features (gender, education, marital status)
- Property area

The target variable is Loan Status, indicating whether a loan is approved or not.

**Data Preprocessing**

Several preprocessing steps were applied to prepare the data for modeling:

- Categorical variables were converted into numerical form using encoding techniques.
- Binary variables were mapped into 0 and 1.
- Multi-category features were transformed into dummy variables.
- Feature scaling was applied to normalize numerical values.

These steps ensure that the model can effectively interpret and learn from the data.

**Model Description**

A Logistic Regression model was used due to its simplicity, interpretability, and effectiveness for binary classification tasks.To address class imbalance, class weighting was applied. This allows the model to give appropriate importance to both approved and rejected loan cases, improving overall fairness and performance.

**Model Performance**

Training Performance
- Accuracy: 0.76.
- ROC-AUC: 0.78.

The model shows strong performance in identifying approved loans while maintaining reasonable balance for rejected cases.

**Testing Performance**
- Accuracy: 0.74
- ROC-AUC: 0.75

The test results are close to training performance, indicating good generalization and minimal overfitting.

**Key Insights**

- The model performs well in predicting loan approvals (class 1).
- Performance for loan rejections (class 0) is moderate but improved compared to an unbalanced approach.
- Applying class balancing helped reduce bias toward the majority class.
- ROC-AUC scores indicate the model has a good ability to distinguish between classes.

**Model Evaluation**

Confusion matrices and ROC curves were used to evaluate model performance:
- The confusion matrix shows a balanced distribution of predictions across both classes
- ROC curves demonstrate consistent performance between training and testing datasets

**Conclusion**

This project demonstrates how Logistic Regression can be effectively used for loan approval prediction. By handling class imbalance and applying proper preprocessing, the model achieves a balanced and reliable performance.
