# 🧬 Protein Stability Prediction Using Machine Learning

## Project Overview
This project uses machine learning to predict protein mutation-associated ddG values. An XGBoost regression model predicts ddG based on mutation-related and structural features. A Streamlit web application provides an interactive interface for generating predictions.

## Technologies Used
- Python, Pandas, NumPy
- Scikit-learn, XGBoost
- Matplotlib, Seaborn
- Streamlit, Joblib

## Input Features
- Wild-type and mutant amino acids
- Mutation position
- Secondary structure
- Conservation score
- Back-to-consensus status
- Essentiality indicator

**Target:** ddG (change in free energy associated with a mutation).

## Machine Learning Workflow
1. Data cleaning and preprocessing
2. Feature selection and protein-wise train-test splitting
3. Training and comparison of regression models
4. Evaluation using MAE, RMSE, and R²
5. Saving the trained model using Joblib
6. Deploying an interactive Streamlit application

## Run Locally
# Install the dependencies:
  pip install -r requirements.txt

# Run the application:
  streamlit run app.py


## Limitations
  Predictions are estimates and require experimental validation. The ddG sign convention and units should be verified using the source dataset documentation before interpreting results.


*Educational project exploring machine learning applications in protein stability prediction.*
