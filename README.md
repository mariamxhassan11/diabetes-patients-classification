# Diabetes Patients Diagnostic Classification

Diagnostic machine learning pipeline predicting diabetes onset based on clinical laboratory measurements.

## Project Structure

```text
04_Diabetes_Patients_Classification/
├── diabetes_patients_classification_data.csv
├── diabetes_patients_classification_pipeline.ipynb
├── app.py
├── best_model.pkl
├── model_metadata.json
├── requirements.txt
└── README.md
```

## Dataset & Features

- **Dataset File:** `diabetes_patients_classification_data.csv`
- **Task Type:** `Classification`
- **Target Variable:** `outcome`
- **Numerical Features (8):** `pregnancies, glucose, blood_pressure, skin_thickness, insulin, bmi, diabetes_pedigree_function, age`
- **Categorical Features (0):** ``

## Model Evaluation Summary

- **Selected Best Model:** `LogisticRegression`

| Metric | Score |
| :--- | :--- |
| `accuracy` | `0.9778` |
| `f1_score` | `0.9667` |
| `roc_auc` | `0.9977` |

## Quickstart & Deployment

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the Streamlit web application:
   ```bash
   streamlit run app.py
   ```
