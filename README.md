# Diabetes Classification with MLflow

This project demonstrates how to manage the Machine Learning (ML) lifecycle using MLflow. It includes data preprocessing, model training, evaluation, and experiment tracking for a diabetes classification task using a Random Forest classifier.

## Project Structure

```
mlops-mlflow-project/
├── data/                  # Contains the dataset (diabetes.csv)
├── notebooks/             # Jupyter notebook with MLflow code
├── mlruns/                # MLflow-generated tracking logs
├── models/                # (Optional) Saved model artifacts
├── artifacts/             # (Optional) Extra MLflow artifacts
├── requirements.txt       # List of required packages
└── README.md              # Project overview and instructions
```

## Dataset

- `data/diabetes.csv`: The dataset used is the Pima Indians Diabetes Dataset.
- Columns include: Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age, Outcome.

## Getting Started

### 1. Install Requirements

```bash
pip install -r requirements.txt
```

### 2. Run the Notebook

```bash
jupyter notebook notebooks/experiment_tracking.ipynb
```

### 3. Launch MLflow Tracking UI

```bash
mlflow ui
```

Then open your browser and go to: http://127.0.0.1:5500

## MLflow Logging

During training, the following are tracked:
- Parameters (e.g., number of estimators)
- Metrics (e.g., accuracy)
- Model artifact

You can explore all these through the MLflow UI.

## Tools & Libraries

- Python
- Pandas
- Scikit-learn
- MLflow
- Jupyter Notebook

## Author

Abdullah Zimmo
