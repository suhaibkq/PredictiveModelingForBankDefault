# 💳 German Credit Risk Prediction

## 📌 Problem Statement

When a bank receives a loan application, it faces a critical decision: approve the loan and risk default, or reject a good applicant and lose potential business. The goal of this project is to build a machine learning model that predicts whether a loan applicant poses a high or low credit risk.

## 🎯 Objective

To develop a classification model that can predict the likelihood of a loan applicant defaulting, using demographic and financial information. This will help HRE Bank automate credit decisions and minimize financial risk.

## 📊 Dataset

- **Source**: `German_Credit.csv`
- **Target Variable**: `Risk` (values: `good` or `bad`)
- **Features Include**:
  - `Age`: Applicant’s age
  - `Sex`: Gender
  - `Job`: Job type (0 = unskilled non-resident, 3 = highly skilled)
  - `Housing`: Type of housing (own, rent, free)
  - `Saving accounts`, `Checking account`: Financial standing
  - `Credit amount`: Loan amount requested
  - `Duration`: Loan duration in months
  - `Purpose`: Purpose of the loan (car, radio/TV, education, etc.)

## 🧪 Project Workflow

1. **Data Understanding & Cleaning**
   - Checked for nulls and inconsistencies.
   - Imputed missing values for savings and checking accounts.

2. **Exploratory Data Analysis (EDA)**
   - Visualized credit amount distribution and default patterns.
   - Identified correlation patterns between features and target.

3. **Feature Engineering**
   - Converted categorical features using one-hot encoding.
   - Normalized numerical values for consistency.

4. **Model Building**
   - Evaluated multiple classifiers: Logistic Regression, Decision Trees, Random Forest, and KNN.
   - Used GridSearchCV for hyperparameter tuning.
   - Split data into training and test sets (e.g., 70/30).

5. **Model Evaluation**
   - Metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC
   - Used Confusion Matrix and ROC curves for visual evaluation.

## 🏆 Results

- **Best Model**: (e.g., Random Forest Classifier)
- **Accuracy**: ~X%
- **Precision / Recall / F1-Score**: From final evaluation
- **Insights**:
  - Age, Job Type, and Credit Amount were significant predictors.
  - Applicants with no savings/checking accounts were more likely to default.

## 📁 Repository Structure

├── Case_study_1_AIML_ETMT_Practice_EXcercise_Week3_.ipynb
├── German_Credit.csv
├── README.md


## 🔍 Key Takeaways

- Machine learning can help financial institutions automate loan decisions.
- Proper preprocessing and feature selection improve model accuracy.
- The balance between precision and recall is crucial in financial risk models.

## 🚀 Future Enhancements

- Integrate model into a loan application dashboard using Streamlit.
- Add more features such as employment history or external credit scores.
- Use advanced models like XGBoost or ensemble stacking for better accuracy.

## 👨‍💻 Author

**[Suhaib Khalid]**  
Machine Learning & Financial Modeling Enthusiast
