# Employee-Salary-Prediction

This project aims to predict whether an employee earns more than $50K per year based on demographic and employment-related attributes using machine learning and deep learning algorithms.
We used a real-world dataset (adult.csv) containing features such as:

  1) Age  
  2) Hours-per-week  
  3) Gender  
  4) Education  
  5) Occupation  
  6) Income class (Target)
  
The data underwent cleaning, encoding (One-Hot Encoding), and scaling before being fed into multiple models including:

  1) Logistic Regression
  2) Decision Tree
  3) Random Forest
  4) Neural Network (Deep Learning)

After evaluating all models, the best-performing model was saved and integrated with a Streamlit-based web application. This app allows users to input employee attributes and get:
  1) A predicted salary class (>50K or ≤50K)
  2) A confidence score showing the model’s certainty
