# Bird Strikes in Aviation: Aircraft Collision Modeling

This project analyzes real-world bird strike incidents reported in U.S. aviation between 2000 and 2011. Using data from the Federal Aviation Administration (FAA), the notebook presents a complete machine learning workflow to model, predict, and gain insights into aircraft collision risks caused by birds on an imbalanced dataset.

---

## 📊 Overview

The notebook walks through the full data science and machine learning pipeline:

1. **Understanding the Dataset**  
   - FAA bird strike dataset (2000–2011)  
   - Data source: Federal Aviation Administration  
   - Problem: Predict and analyze patterns in bird strike incidents.

2. **Data Preprocessing**  
   - Duplicate and missing data handling  
   - Quality filtering and outlier detection  
   - Encoding categorical variables  
   - Handling imbalanced classes

3. **Feature Engineering**  
   - Feature selection techniques  
   - Domain-informed variable transformation

4. **Modeling & Evaluation**  
   - Baseline model evaluation  
   - Training and tuning multiple ML models  
     - Logistic Regression  
     - Random Forest  
     - XGBoost  
   - Hyperparameter optimization  
   - Ensemble modeling for performance boosting

5. **Conclusion & Insights**  
   - Summary of key findings  
   - Model performance comparison  
   - Suggested future directions

---

## 🧰 Technologies Used

- Python 
- Libraries:  
  `pandas`, `numpy`, `scikit-learn`, `xgboost`, `matplotlib`, `seaborn`, `scipy`

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/bird-strike-modeling.git
   cd bird-strike-modeling
