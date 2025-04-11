# 🎯 Student Math Score Prediction

## 📘 Project Overview
This project uses machine learning algorithms to predict students' **math scores** based on demographic and educational features such as **gender**, **parental education level**, **lunch type**, and **test preparation course**.

The goal is to identify the key factors that influence academic performance and build a predictive model to support educators and decision-makers.

---

## 🧪 Models Tested

| Model                     | R-squared | MSE   |
|--------------------------|-----------|--------|
| Linear Regression         | **0.88**  | 29.10 |
| Random Forest             | 0.85      | 36.66 |
| XGBoost                   | 0.83      | 42.32 |
| Decision Tree             | 0.73      | 64.72 |
| Support Vector Machine    | 0.66      | 83.24 |

✅ **Linear Regression** was the best-performing model.

---

## 📂 Files in This Repository
- `project_code.ipynb`: Full code with data processing, analysis, modeling, and evaluation.
- `students_scores.csv`: The dataset used in the project.
- `README.md`: Project overview, usage instructions, and results.
- Blog post: See below ⬇️

---

## 📈 Feature Importance
Using the Random Forest model, the most influential features were:
- Test preparation course ✅
- Gender
- Parental level of education

These features had the highest impact on predicting student math scores.

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/student-math-score-prediction.git
