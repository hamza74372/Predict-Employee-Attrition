# Predict-Employee-Attrition
# Employee Attrition Prediction System

![HR Analytics](https://img.shields.io/badge/domain-HR%20Analytics-blueviolet)
![Python](https://img.shields.io/badge/python-3.8%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)

A machine learning solution to predict employee attrition and provide actionable HR insights using the IBM HR Analytics dataset.

## ✨ Key Features

- **Predictive Modeling**: Random Forest and Logistic Regression implementations
- **Explainable AI**: SHAP values for model interpretability
- **Class Imbalance Handling**: SMOTE oversampling technique
- **Actionable Insights**: Clear HR recommendations
- **Production-Ready**: Includes model serialization

## 🛠️ Installation

### Google Colab
1. Upload your `kaggle.json` when prompted
2. Run all cells sequentially

### Local Setup
```bash
git clone https://github.com/yourusername/employee-attrition-prediction.git
cd employee-attrition-prediction

# Create virtual environment (recommended)
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

pip install -r requirements.txt
