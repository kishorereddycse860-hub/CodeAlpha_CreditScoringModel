# 💳 Credit Scoring Model
### CodeAlpha Machine Learning Internship — Task 1

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Objective
Predict an individual's creditworthiness (loan default risk) using past financial data.

---

## 📊 Dataset
- **Source:** [Credit Risk Dataset — Kaggle](https://www.kaggle.com/datasets/laotse/credit-risk-dataset)
- **Rows:** 32,581
- **Columns:** 12
- **Target:** `loan_status` (0 = No Default, 1 = Default)

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Pickle

---

## 🔄 Project Workflow
1. Exploratory Data Analysis (EDA)
2. Data Preprocessing — null handling, outlier removal
3. Feature Engineering — debt-to-income ratio, income per emp year
4. Model Training — Logistic Regression, Decision Tree, Random Forest
5. Model Evaluation — Precision, Recall, F1-Score, ROC-AUC
6. Interactive Prediction System — user input based

---

## 📈 Model Results

| Model | ROC-AUC |
|-------|---------|
| Logistic Regression | ~0.78 |
| Decision Tree | ~0.82 |
| Random Forest | ~0.93 |

✅ **Random Forest** achieved the best performance.

---

## 🔍 Key Features
- `loan_percent_income` — strongest predictor of default
- `loan_int_rate` — higher rate = higher risk
- 
- `loan_grade` — direct creditworthiness indicator

---

## 🚀 How to Run
```bash
# Clone the repo
git clone https://github.com/kishorereddycse860-hub/CodeAlpha_CreditScoringModel.git

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn

# Open notebook
jupyter notebook CODE_ALPHA_task\ 1.ipynb
```

---

## 📂 Project Structure

---

## 👨‍💻 Author
**Kishore Reddy**  
B.Tech CSE (AI/ML) — Marwadi University  
[LinkedIn](https://www.linkedin.com/in/kishore-reddy-gayam-867254316)

---

*This project was completed as part of the CodeAlpha Machine Learning Internship.* 
