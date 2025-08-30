# Healthcare Data Analysis & Prediction Models

This project contains machine learning models for healthcare data analysis, focusing on heart disease prediction and insurance cost estimation.

## 📊 Datasets

### Heart Disease Dataset (`heart.csv`)
- **Size**: 920 records
- **Purpose**: Predict heart disease occurrence
- **Features**:
  - Age, Sex, Chest Pain Type
  - Resting Blood Pressure, Cholesterol levels
  - Fasting Blood Sugar, Resting ECG
  - Maximum Heart Rate, Exercise Angina
  - ST Depression (Oldpeak), ST Slope
  - Target: HeartDisease (0/1)

### Insurance Dataset (`insurance.csv`)
- **Size**: 1,340 records  
- **Purpose**: Predict insurance charges
- **Features**:
  - Age, Sex, BMI, Children count
  - Smoker status, Region
  - Target: Insurance charges (continuous)

## 🔧 Project Structure

```
├── heart.csv              # Heart disease dataset
├── insurance.csv           # Insurance cost dataset
├── insurance_model.ipynb   # Jupyter notebook for model development
└── README.md              # Project documentation
```

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

### Usage
1. Clone or download the repository
2. Open `insurance_model.ipynb` in Jupyter Notebook
3. Run the cells to explore data and train models

## 📈 Potential Analysis

### Heart Disease Prediction
- Binary classification problem
- Features include vital signs and medical test results
- Can help identify patients at risk

### Insurance Cost Prediction
- Regression problem
- Factors affecting insurance premiums
- Useful for pricing strategies and risk assessment

## 🛠 Suggested Models

- **Classification**: Logistic Regression, Random Forest, SVM
- **Regression**: Linear Regression, Random Forest, Gradient Boosting
- **Evaluation**: Accuracy, Precision, Recall, F1-Score, RMSE, R²

## 📋 Next Steps

1. Exploratory Data Analysis (EDA)
2. Data preprocessing and feature engineering
3. Model training and evaluation
4. Hyperparameter tuning
5. Model comparison and selection

## 📝 Notes

- Ensure proper data preprocessing for categorical variables
- Handle missing values appropriately
- Consider feature scaling for certain algorithms
- Validate models using cross-validation

---

*This project is for educational and research purposes in healthcare analytics.*