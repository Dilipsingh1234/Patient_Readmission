# Patient Readmission Risk Prediction

This project predicts whether a hospital patient is at risk of readmission using structured clinical and demographic data. The workflow follows a complete data science lifecycle, including EDA, feature engineering, model training, model evaluation, and model testing.

## Project Workflow

1. **EDA**  
   Explored patient demographics, diagnosis patterns, treatment types, length of stay, previous readmissions, and other factors related to readmission.

2. **Feature Engineering**  
   Created date-based features from admission date, removed unnecessary columns, handled categorical and numerical features, and split the dataset into training and testing files.

3. **Model Training**  
   Compared Logistic Regression, Random Forest, and Gradient Boosting models using accuracy, precision, recall, F1-score, and ROC-AUC.

4. **Model Testing**  
   Loaded the saved model and evaluated it on unseen test data. Patient-level prediction probabilities were also generated.

## Best Model

The best-performing model was **Gradient Boosting**.

- Accuracy: 81.25%
- Precision: 84.12%
- Recall: 93.37%
- F1 Score: 88.51%
- ROC-AUC: 82.88%

## Healthcare Relevance

In a healthcare readmission problem, recall is especially important because missing a high-risk patient could mean missing an opportunity for follow-up care. This project shows how machine learning can support risk analysis, prevention, and outcome improvement by helping identify patients who may need additional attention after discharge.