# 2-Week Intensive Sprint Plan

## Daily Breakdown

### Week 1: Data & Models

#### Day 1-2 (Setup & Data Acquisition)
**All Teams:**
- Set up development environment
- Install Python, Jupyter, dependencies
- Download CICIDS2017 dataset
- Initial data exploration

**Data Engineers (Johnson, Ambrose):**
- Set up data folders
- Load and inspect raw dataset
- Document dataset schema

#### Day 3-4 (Data Preprocessing)
**Data Engineers (Johnson, Ambrose):**
- Handle missing values
- Remove duplicates
- Normalize numeric fields
- Encode categorical features
- Split train/test (70/30)
- Save cleaned dataset

**ML Engineers (Christine, Cosma):**
- Review cleaned data
- Begin feature correlation analysis

#### Day 5-7 (Feature Engineering & Model Training)
**ML Engineers (Christine, Cosma):**
- Feature selection (correlation analysis, PCA)
- Train 6 models:
  1. Logistic Regression
  2. Naive Bayes
  3. Decision Tree
  4. Random Forest
  5. SVM
  6. Gradient Boosting/XGBoost
- Hyperparameter tuning with GridSearchCV
- Save models using joblib

**Dashboard Developers (Grace, Lailah):**
- Design dashboard mockups
- Set up Streamlit project structure

### Week 2: Integration & Deployment

#### Day 8-9 (Evaluation & Backend)
**ML Engineers (Christine, Cosma):**
- Evaluate all models (accuracy, precision, recall, F1, ROC-AUC)
- Select best model
- Create evaluation report

**Dashboard Developers (Grace, Lailah):**
- Build Flask/FastAPI backend
- Create `/predict` endpoint
- Load best model into API
- Test API with sample data

#### Day 10-11 (Dashboard Development)
**Dashboard Developers (Grace, Lailah):**
- Build Streamlit dashboard
- Real-time traffic visualization
- Prediction display (Normal vs Attack)
- Alert logs
- Performance metrics charts
- Connect to backend API

**Data Engineers (Johnson, Ambrose):**
- Support dashboard with data formatting
- Prepare sample live data

#### Day 12-13 (Integration & Deployment)
**All Teams:**
- Integrate all components
- End-to-end testing
- Fix bugs
- Create Dockerfiles
- Write docker-compose.yml
- Test Docker deployment
- Performance optimization

#### Day 14 (Documentation & Demo)
**All Teams:**
- Finalize documentation
- Prepare presentation slides
- Set up live demo
- Rehearse presentation
- Final testing

## Parallel Work Strategy

### Week 1
- **Data Engineers**: Focus on data pipeline (Days 1-4)
- **ML Engineers**: Join on Day 3, lead Days 5-7
- **Dashboard Developers**: Planning and setup (Days 1-7)

### Week 2
- **ML Engineers**: Evaluation (Days 8-9), then support integration
- **Dashboard Developers**: Backend and UI (Days 8-11)
- **All Teams**: Integration and deployment (Days 12-14)

## Critical Success Factors
1. **Communication**: Daily standups (15 min)
2. **Version Control**: Commit code daily
3. **Documentation**: Document as you go
4. **Testing**: Test each component before integration
5. **Time Management**: Stick to daily goals

## Emergency Contingencies
- If dataset too large → Use sampling
- If models too slow → Focus on Random Forest only
- If Docker issues → Deploy locally first
- If integration delays → Simplify dashboard features
