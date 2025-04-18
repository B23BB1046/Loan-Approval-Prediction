# Loan Approval Prediction

## Project Overview
This project aims to predict the approval status of a loan application based on applicant information using machine learning techniques. By analyzing various features such as income, education, credit history, and loan amount, the system classifies whether a loan should be approved or not. The goal is to assist financial institutions in automating the decision-making process, thereby improving efficiency and consistency.

## Key Features
1. **Data Preprocessing:**
   - Handling missing values and outliers.
   - Encoding categorical variables using Label Encoding and One-Hot Encoding.
   - Feature scaling using StandardScaler.

2. **Machine Learning Models:**
   - Logistic Regression
   - K-Nearest Neighbors (KNN)
   - Decision Tree
   - Random Forest
   - Support Vector Machine (SVM)

3. **Dataset:**
   - The dataset consists of loan application data with various features such as gender, marital status, education, employment, income, loan amount, and credit history.
   - The target variable is `Loan_Status` indicating whether a loan was approved (`Y`) or not (`N`).

4. **Evaluation Metrics:**
   - Accuracy
   - Precision
   - Recall
   - F1-Score
   - Confusion Matrix

## Prerequisites
- Python (version 3.8 or above)
- Libraries:
  - NumPy
  - Pandas
  - Scikit-learn
  - Matplotlib
  - Seaborn

## How to Run
1. Load the dataset and perform data cleaning and preprocessing.
2. Train the machine learning models using the training script.
3. Evaluate model performance on the test set using the provided evaluation functions.
4. Compare metrics across models to determine the best-performing algorithm.

## Results
Among all models tested, the Random Forest Classifier provided the most balanced performance in terms of accuracy, precision, and recall. Logistic Regression and SVM also performed well, while Decision Tree and KNN showed moderate performance.

## Future Work
- Implement ensemble methods like Gradient Boosting and XGBoost for potential performance improvement.
- Integrate the model into a web application for real-time predictions.
- Perform hyperparameter tuning using techniques such as Grid Search and Random Search.
- Add explainability using SHAP or LIME for model decisions.

## Contact
For queries or collaboration, feel free to contact:  
**Yogendra**  
Student of Bioscience and Bioengineering, IIT Jodhpur  
Email: b23bb1046@iitj.ac.in

---
*"This project demonstrates the potential of machine learning in automating financial decision-making, offering consistent and efficient predictions for loan approvals."*
