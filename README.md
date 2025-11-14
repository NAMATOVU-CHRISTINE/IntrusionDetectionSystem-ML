# Intrusion Detection System (IDS) Using Machine Learning

## Project Overview
A Machine Learning-based Intrusion Detection System capable of detecting malicious network traffic in real time.

## Team

### Machine Learning Engineers
- **Christine** & **Cosma**: Data preprocessing, feature engineering, model training (Random Forest, SVM, Logistic Regression, Gradient Boosting), hyperparameter tuning, model evaluation (accuracy, precision, recall, F1-score), anomaly detection, model export using joblib, ML documentation

### Data Engineers
- **Johnson** & **Ambrose**: Dataset management (CICIDS2017, Wireshark), data cleaning, filtering, transformation, data ingestion pipelines, preprocessing pipelines, handling missing values, encoding categorical fields, dataset versioning, data quality assurance

### Dashboard Developers
- **Grace** & **Lailah**: Streamlit dashboard design and development, charts, metrics, alerts, logs UI, backend ML API integration, real-time network traffic visualization, intrusion alerts display, UX/UI improvements

## Project Structure
```
ids-ml-project/
├── data/              # Raw and processed datasets
├── notebooks/         # Jupyter notebooks for exploration
├── models/            # Trained model files
├── app/              
│   ├── backend/       # Flask/FastAPI backend
│   └── dashboard/     # Streamlit dashboard
├── docs/              # Documentation
└── requirements.txt   # Python dependencies
```

## Timeline (2 Weeks - Intensive Sprint)

### Week 1
- **Days 1-2**: Project setup, dataset acquisition, initial data exploration
- **Days 3-4**: Data preprocessing, cleaning, feature engineering
- **Days 5-7**: Model training (all 6 models), hyperparameter tuning

### Week 2
- **Days 8-9**: Model evaluation, best model selection, API backend development
- **Days 10-11**: Dashboard development, real-time visualization
- **Days 12-13**: System integration, testing, Docker deployment
- **Day 14**: Final documentation, presentation preparation, demo

## Getting Started
See [docs/setup.md](docs/setup.md) for installation instructions.

## Target Deliverables
- ✅ 6 trained ML models (Logistic Regression, Naive Bayes, Decision Tree, Random Forest, SVM, Gradient Boosting)
- ✅ REST API backend (Flask/FastAPI)
- ✅ Real-time Streamlit dashboard
- ✅ Docker deployment
- ✅ Complete documentation
- ✅ Live demonstration
