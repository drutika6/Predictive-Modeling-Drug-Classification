#  Predictive Modeling for Drug Classification

A Machine Learning project that predicts the type of drug to prescribe based on a patient's medical information.

---

##  Project Overview

Drug prescription depends on several patient characteristics such as age, sex, blood pressure, cholesterol level, and sodium-to-potassium ratio. This project builds multiple Machine Learning models to classify the appropriate drug based on these medical attributes.

---

##  Objectives

- Perform data preprocessing
- Train multiple Machine Learning models
- Compare model performance
- Predict drug type accurately
- Visualize feature importance and confusion matrices

---

##  Dataset Features

| Feature | Description |
|----------|-------------|
| Age | Patient Age |
| Sex | Gender |
| BP | Blood Pressure |
| Cholesterol | Cholesterol Level |
| Na_to_K | Sodium to Potassium Ratio |

### Target

Drug Type

---

##  Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib

---

##  Machine Learning Models

- Decision Tree Classifier
- Random Forest Classifier
- Logistic Regression

---

##  Results

| Model | Accuracy |
|--------|----------|
| Decision Tree | 97.50% |
| Random Forest | 97.50% |
| Logistic Regression | 97.50% |

Random Forest model was selected and saved for future predictions.

---

##  Project Structure

```
Predictive-Modeling-Drug-Classification/
│
├── data/
│   └── drug200.csv
│
├── models/
│   └── random_forest_model.pkl
│
├── notebook/
│   └── Drug_classification.ipynb
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

##  Project Outputs

### Random Forest Accuracy

97.50%

### Confusion Matrix

(Add screenshot here)

### Feature Importance

(Add screenshot here)

### Model Accuracy Comparison

(Add screenshot here)

---

##  Future Improvements

- Deploy using Streamlit
- Flask REST API
- Hyperparameter tuning
- Cross-validation
- Interactive web interface

---

##  Author

**Drutika**

GitHub:
https://github.com/drutika6
##  Project Outputs

### Random Forest Accuracy

![Accuracy](images/accuracy.png)

### Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

### Feature Importance

![Feature Importance](images/feature_importance.png)

### Model Comparison

![Comparison](images/comparison.png)
---

