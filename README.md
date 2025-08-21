# Heart-Disease-Prediction
Predicting heart disease from clinical features with Python (EDA, Logistic Regression baseline, and a high-performing Random Forest), including ROC curves, confusion matrices, and feature importance. 

Heart Disease Prediction (ML)
This project explores whether common clinical attributes (age, chest pain type, cholesterol, max heart rate, etc.) can predict the presence of heart disease. We perform EDA, train/test split (80/20), and compare models:

Models: Logistic Regression (baseline) and Random Forest

Results: Logistic Regression ≈ 79.5% accuracy; Random Forest ≈ 98.5% accuracy with strong ROC/AUC and clear feature importances (e.g., chest pain type, vessels colored, max heart rate). 

Stack: Python, pandas, scikit-learn, matplotlib/seaborn

What’s inside:

EDA (distributions, correlation heatmap, class comparisons)

Training scripts/notebooks, metrics (confusion matrix, ROC), feature importance

Reproducible split with random_state=42

How to run

git clone https://github.com/<your-username>/<repo>.git
cd <repo>
pip install -r requirements.txt  # pandas, scikit-learn, matplotlib, seaborn, numpy
# Option A: run notebook
# Option B: run a script, e.g.:
python train.py
