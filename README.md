# Multiple-Linear-regression-Diabetes-Dataset
🩺 Multiple Linear Regression on Diabetes Dataset

📌 Project Overview

This project implements Multiple Linear Regression using both:

- ✅ From Scratch (using Normal Equation)
- ✅ Scikit-Learn ("LinearRegression")

The objective is to predict disease progression in diabetic patients based on medical features.

---

📂 Dataset Information

This project uses the Diabetes Dataset from "sklearn.datasets".

- Total Samples: 442
- Features: 10
- Target: Disease progression after one year

🔑 Features:

- "age", "sex", "bmi", "bp", "s1" to "s6"

🎯 Target:

- "target" → Quantitative measure of disease progression

---

⚙️ Approach

1️⃣ From Scratch Implementation (Normal Equation)

Implemented Linear Regression using the closed-form solution:

[
\beta = (X^T X)^{-1} X^T y
]

- Direct computation of coefficients
- No iterative training required
- Based on linear algebra concepts

---

2️⃣ Using Scikit-Learn

- Used "LinearRegression" from sklearn
- Compared results with scratch implementation

---

📊 Workflow

1. Load dataset using "load_diabetes()"
2. Convert into pandas DataFrame
3. Train-test split
4. Train models:
   - Scratch (Normal Equation)
   - Sklearn model
5. Make predictions
6. Evaluate performance

---

📈 Evaluation Metrics

- MAE: ~45.21
- MSE: ~3094.46
- R² Score: ~0.44

👉 The model achieves an R² score of approximately 0.44, indicating moderate predictive performance and explaining about 44% of the variance in the target variable.

---

📉 Visualization

🔹 Actual vs Predicted Plot

- Scatter plot comparing actual vs predicted values
- Red dashed line represents ideal prediction line (y = x)

👉 Observation:
The plot shows moderate alignment along the diagonal, indicating that the model captures the general trend but has noticeable prediction errors.

---

🧠 Key Learnings

- Understanding of Normal Equation (closed-form solution)
- Difference between:
  - Mathematical implementation
  - Library-based implementation
- Importance of model evaluation using metrics
- Visualization for model performance analysis

---

🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

▶️ How to Run

git clone <your-repo-link>
cd Multiple-Linear-Regression
pip install -r requirements.txt
python train.py

---

📌 Future Improvements

- Implement Gradient Descent version
- Apply feature scaling
- Try Ridge/Lasso Regression
- Improve model performance

---

🔗 Dataset Source

https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_diabetes.html

---

🙌 Acknowledgment

This project is part of my learning journey in Machine Learning and Data Science.Predicting Diabetes Progression based on 10 features 
