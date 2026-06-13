# Heart Disease Classification

Predicting heart disease presence using clinical features with 
machine learning classification and Optuna hyperparameter tuning.

## Dataset
- **Source**: UCI Machine Learning Repository
- **Download**: https://archive.ics.uci.edu/ml/machine-learning-databases/heart-disease/processed.cleveland.data
- **Size**: ~300 patients, 13 clinical features
- **Target**: Heart disease presence (0=No, 1=Yes)

# Results
<img width="2085" height="1785" alt="heart_disease_analysis" src="https://github.com/user-attachments/assets/3e4925be-a3e9-4ec6-9643-7a0711fc3aaa" />

## Models
| Model | Accuracy | F1 Score | ROC AUC |
|-------|----------|----------|---------|
| Logistic Regression | 0.82 | 0.82 | 0.88 |
| Random Forest | 0.85 | 0.85 | 0.91 |
| RF (Optuna-Tuned) | 0.86 | 0.86 | 0.92 |

## How to Run
```bash
pip install -r requirements.txt
python main.py
