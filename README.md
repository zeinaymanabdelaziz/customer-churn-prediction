# Customer Churn Prediction

A machine learning project focused on predicting customer churn in the telecommunications sector.  
<br>Developed to help businesses identify at-risk customers and support proactive retention strategies.

# Project Overview

This project analyzes telecom customer behavior to predict the likelihood of churn (customer leaving the service).  
<br>The goal is to enable telecom providers to take preventive action through targeted retention efforts.

# Techniques Applied

- ✅ Data preprocessing & feature engineering
- ✅ Handled class imbalance using **SMOTE**
- ✅ Model comparison: Decision Tree, Naive Bayes, Random Forest, SVM
- ✅ ROC-AUC analysis for performance evaluation

# Models Evaluated

| Model            | Evaluation Metric | Notes                                   |
|------------------|-------------------|-----------------------------------------|
| Decision Tree    | ROC-AUC           | Interpretable but may overfit           |
| Naive Bayes      | ROC-AUC           | Fast and simple, assumes feature independence |
| Random Forest    | ROC-AUC           | Robust with better generalization       |
| SVM              | ROC-AUC           | Good with high-dimensional spaces       |

✅ **Best Model**: Based on ROC-AUC performance and generalization, **Random Forest** showed consistent results across validation.

# Technologies Used

- **Python**
- **Pandas**, **NumPy** – Data manipulation
- **Scikit-learn** – ML models and evaluation
- **Imbalanced-learn** – SMOTE for class balancing
- **Matplotlib**, **Seaborn** – Visualization
- **Jupyter Notebook** – Development environment

# Project Structure

📦 Customer_Churn_Prediction
<br>├── Customer_Churn_Prediction_Code.ipynb # Jupyter notebook with full pipeline

# Use Cases

- Detect customers likely to churn and target them with retention offers
- Gain insights into important features influencing churn
- Support customer success and marketing teams with data-driven decisions

# Future Improvements

- Hyperparameter tuning using GridSearchCV
- Feature selection and dimensionality reduction
- Integration with CRM systems for real-time predictions
- Deploy as a web service using Flask or Streamlit

 # License
<br>This project is intended for academic and educational use only.
