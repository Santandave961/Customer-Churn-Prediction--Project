# Customer-Churn-Prediction--Project
### Project Overview
Customer churn is a major challenge for subscription-based businesses like telecom companies. This project builds an end to end machine learning model to predict whether a customer is likely to churn (leave the company) or stay, based on their usage patterns, account details, and demographics.The insights gained can help business implement targeted retention strategies and reduce revenue loss
The project demonstrates:
- Data cleaning and preprocessing
- Explanatory Data Analysis (EDA)
- Feature engineering
- Machine learning classification models ( Logistic Regression, Random Forest, XGBoost)
- Model evaluation (Accuracy, F1 Score, ROC-AUC)
- Visualization of results

### Key Objectives:
- Analyze customer behaviour patterns
- Build predictive models to identify at risk customers
- Compare performance of different machine learning algorithms
- Provide actionable insights for customer retention.

### Dataset
The dataset used is the Telco Customer Churn dataset:
Source: Kaggle - Telco Customer Churn
Rows: 7043
Features: 21 (Customer demographics, account info, services subscribed,etc)
Target Variable: Churn (Yes/No)

### Tech Stack
1. Programming Language: Python
2. Libraries:
  - pandas, numpy for data manipulation
  - matplotlib, seaborn for visualization
  - scikit-learn for ML models and evaluation
  - Xgboost for boosting models
  - Streamlit (optional) for interactive deployment

### Project Workflow
1. Data Cleaning and Preprocessing:
  - Removed missing values and duplicates.
  - Converted categorical features using Label encoding
  - Scaled numeric features with StandardScaler
2. Explanatory Data Analysis (EDA)
  - Visualised churn rate by contract type, payment method and monthly charges.
  - Found that month-to-month contracts had the highest churn rates
3. Feature Enineering
  - Created tenure groups
  - Calculated total services subscribed per customer
4. Model Training
  - Trained 3 models for comparisons:
  - Logistic Regression
  - Random Forest
  - XGBoost
5. Model Evaluation
  - Metrics used: Accuracy, Precision, Recall. F1 Score, ROC-AUC
  - XGBoost performed best with :
  - Accuracy : ~80%
  - ROC-AUC : ~0.84
6. Visualisation
  - Confusion matrix for best model
  - Churn distribution plots

### Results
Key Insights
- XGBoost achieved the highest performance across all metrics
- Feature importance : Contract type, tenure and monthly charges are top predictors.
- Business Impact : Model can identify ~85% of potential churners correctly.

### Future Improvements:
1. Hyperparameter tuning for better accuracy
2. Add deep learning models (Neural Networks)
3. Build a Streamlit dashboard to allow interactive churn predictions.
   
   
### Contributions
Contributions are welcome! Here's how you can help:
1. Fork the repository
2. Create a feature branch
3. Commit your changes.
4. Push to the branch.
5. Open a Pull Request.

   
### Contact
E-mail : wisdomokparaji@gmail.com
LinkedIn Name : Okparaji Wisdom

### Acknowledgements
- Kaggle for providing the datasets
- Scikit learn for machine learning tools
- XGBoost for gradient boosting implementation


   
