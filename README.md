Heart Disease Classification Project
Overview
This repository contains code, notebooks, and experiments for analyzing patient characteristics and clinical measurements to predict the presence or absence of heart disease.
Objectives
Explore and clean clinical data
Visualize feature distributions and relationships
Train and evaluate classification models
Compare model performance using common metrics
Build a reproducible and secure machine learning workflow
Technology Stack
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Project Structure
```text
.
├── README.md
├── requirements.txt
├── data/
│   ├── raw/
│   └── processed/
├── notebooks/
├── src/
│   ├── data/
│   ├── features/
│   ├── models/
│   └── visualization/
├── tests/
└── outputs/
```
Environment Setup
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```
Configuration
Create a `.env` file for local configuration:
```env
ENVIRONMENT=development
DEBUG=false
DATA_PATH=./data
```
Security Guidelines
Never commit passwords, API keys, or datasets containing sensitive information.
Store secrets in environment variables.
Review dependencies regularly and update vulnerable packages.
Follow least-privilege access principles.
Development Workflow
```bash
# Run tests
pytest

# Run a training script
python src/models/train.py
```
Model Evaluation
Recommended metrics:
Accuracy
Precision
Recall
F1 Score
ROC-AUC
Confusion Matrix
Reproducibility
Fix random seeds where appropriate.
Document dataset versions.
Record model parameters and evaluation results.
License
Add the appropriate license before public distribution.
