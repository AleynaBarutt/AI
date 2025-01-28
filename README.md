# Credit Approval Prediction Model

This project focuses on predicting the approval status of credit applications using machine learning models. The goal is to leverage various classifiers to determine whether a loan application is approved or rejected based on demographic, financial, and credit history data. The project demonstrates how machine learning can enhance the credit evaluation process and assist banks in making quicker and more informed decisions.

## Dataset Overview:
The dataset contains several features such as demographic details, financial data, and credit history information:
- **Demographic Features**: Gender, Marital Status, Self-Employment Status, Education, Dependents
- **Financial Features**: Applicant Income, Coapplicant Income, Loan Amount, Loan Term
- **Credit History and Residence**: Credit History, Property Area
- **Target Variable**: Loan Status (Approved or Rejected)

## Data Preprocessing:
- **Handling Missing Values**: Missing data was handled by filling numerical values with the median and categorical values with the mode.
- **Outlier Detection**: Outliers in numeric data were detected and filtered using the Interquartile Range (IQR) method.
- **Categorical Encoding**: Categorical variables were converted to numerical representations to make the data suitable for machine learning models.
- **Feature Scaling**: All numerical features were standardized to ensure better model performance.

## Models Used:
Several machine learning algorithms were used to predict loan approval:
1. **Decision Tree**: A classifier that uses a tree-like structure to make decisions based on feature splits.
2. **Random Forest & Logistic Regression**: Ensemble and statistical models used with financial features to predict loan approval.
3. **Support Vector Machine (SVM)**: A powerful classifier that handles non-linear decision boundaries.
4. **Gradient Boosting & AdaBoost**: Boosting methods that combine weak learners to form a strong classifier.
5. **Ensemble Model (Voting Classifier)**: A combination of the previously mentioned models to create a robust classifier using a majority voting system.

## Evaluation:
The performance of each model was evaluated using several metrics:
- **Accuracy**: Ensemble model achieved the highest accuracy score of 84%.
- **Precision, Recall, F1-Score**: These metrics were calculated for each model and showed that the ensemble approach outperformed individual models.
- **Confusion Matrix**: The confusion matrix was used to visualize the classification results, showing the true positives, true negatives, false positives, and false negatives.

## Results:
The ensemble model, combining Random Forest, Gradient Boosting, SVM, Decision Tree, Logistic Regression, and AdaBoost, performed the best with an accuracy of 84%. This approach provides the most reliable predictions for credit approval, outperforming other models individually.

## Conclusion:
This project demonstrates how machine learning algorithms can be effectively applied to credit evaluation processes. By incorporating demographic, financial, and credit history data, predictive models can help banks make faster and more accurate decisions, reducing risks and improving operational efficiency.


