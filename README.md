# PROJECT_HRA

An HR analytics project focused on employee attrition analysis and churn prediction using the IBM HR Analytics Employee Attrition dataset. The repository combines exploratory analysis notebooks, modeling experiments, and source datasets for people analytics work.

## Project Focus

- HR analytics and people analytics
- Employee attrition and churn prediction
- Exploratory data analysis for workforce patterns
- Supervised machine learning classification
- IBM / Kaggle-style HR analytics datasets

## Dataset

The repository includes IBM HR attrition data under `data/`.

Key dataset details:

- 1,470 employee records
- 35 columns
- Target column: `Attrition`
- Class balance: 237 employees marked `Yes`, 1,233 marked `No`

Example feature areas include age, travel frequency, department, distance from home, job role, job satisfaction, income, tenure, and work-life indicators.

## Problem Statement

Employee attrition can create hiring costs, productivity gaps, and loss of institutional knowledge. This project treats attrition as a supervised learning problem: given employee attributes, can we identify patterns that help predict whether an employee is likely to leave?

## Repository Structure

```text
.
├── data/
│   ├── employee_attrition_ibm_data.csv
│   └── Original_WA_Fn-UseC_-HR-Employee-Attrition.csv
├── [FINAL]Modeling_1_0.ipynb
├── Baseline_1.ipynb
├── R_notebook_01.ipynb
├── R_script_01.ipynb
├── corr-heat.png
└── tmp/
```

## Typical Workflow

1. Load and inspect the HR dataset
2. Clean fields and prepare categorical variables
3. Explore attrition trends by role, income, satisfaction, age, distance, and tenure
4. Engineer model-ready features
5. Train baseline classification models
6. Evaluate predictions with accuracy, precision, recall, F1 score, and confusion matrix
7. Interpret the strongest drivers of employee churn

## Suggested Environment

This project is notebook-oriented. A typical Python environment would include:

- Python 3
- Jupyter Notebook
- pandas
- NumPy
- matplotlib
- seaborn
- scikit-learn

## Run Locally

Clone the repository:

```bash
git clone https://github.com/sss2107/PROJECT_HRA.git
cd PROJECT_HRA
```

Start Jupyter:

```bash
jupyter notebook
```

Open the modeling or baseline notebooks and run the analysis from data loading through evaluation.

## Results to Document Next

To make the project even stronger for readers, add:

- A final model comparison table
- Best model and evaluation metrics
- Key attrition drivers discovered during analysis
- Business recommendations for HR teams
- A lightweight `requirements.txt` for reproducibility

## License

This project is licensed under the terms in [LICENSE](LICENSE).
