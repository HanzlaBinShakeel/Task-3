# Task 3: Heart Disease Prediction

## Objective
Binary classification: predict heart disease risk from clinical features.

## Dataset
**UCI Heart Disease (Cleveland)** — 303 patients, 14 attributes. Source: UCI ML Repository.

## Models Applied
| Model | Metrics |
|-------|---------|
| Logistic Regression | Accuracy, ROC-AUC, confusion matrix |
| Decision Tree (max_depth=5) | Feature importance |

## Key Results
- Missing values (`?`) removed; target binarized (0 = healthy, 1 = disease)
- Strong predictors: **cp**, **thalach**, **oldpeak**, **exang**
- ROC curves show good separation; accuracy typically > 80% on hold-out set

## Important
Educational use only — not for clinical diagnosis.

## Files
| File | Description |
|------|-------------|
| `heart_disease_prediction.ipynb` | EDA + modeling notebook |

## Run
```bash
jupyter notebook heart_disease_prediction.ipynb
```
