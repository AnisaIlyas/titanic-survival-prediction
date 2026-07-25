# titanic-survival-prediction[README.md](https://github.com/user-attachments/files/30375610/README.md)
# Titanic Survival Prediction:
A machine learning project predicting passenger survival based on the features provided, comparing multiple classification models and using SHAP for model explainability.

## Problem Statement:
Given passengers details, model predicts whether a passenger survived the Titanic disaster. This project not only focuses on predicting accuracy but also on *why* the model makes the decision it does.

## Key Stack and purpose:
- pandas: data loading, cleaning(handling missing values), feature engineering.
- Scikit-learn: train/test splitting. model training(Decision Tree Classifier, Random Forest, Logistic Regression) and evaluation metrics
- shap: model explainability, showing features drove individual predictions
- matplotlib: visualizing SHAP summary plots
- Jupyter notebook: development and presentation environment

## Getting Started:
```bash
git clone https://github.com/AnisaIlyas/titanic-survival-prediction.git
cd titanic-survival-prediction
pip install -r requirements.txt
jupyter notebook notebook.ipynb
```
## Project type:
personal project, not part of any university assessment

## Developer:
Anisa Ilyas
