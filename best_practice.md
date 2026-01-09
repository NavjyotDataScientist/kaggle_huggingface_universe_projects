# 🧠 Machine Learning Practical Cheat Sheet

This cheat sheet helps you **decide quickly**:
> *“If I see this type of problem → which model / concept should I use?”*

It is designed for **real-world ML work**, Kaggle, GitHub portfolios, and interviews.

---

## 1️⃣ First Question: Do You Have Labels?

| Situation | Choose |
|---------|--------|
| Target variable (y) exists | Supervised Learning |
| No labels | Unsupervised Learning |

---

## 2️⃣ Supervised Learning: Classification vs Regression

| Target Type | Problem Type |
|-----------|-------------|
| Continuous values (price, age) | Regression |
| Categories / classes | Classification |

---

## 3️⃣ Classification Cheat Sheet

### 🔹 How many classes?

| Case | Model | Activation |
|----|------|-----------|
| Binary (2 classes) | Logistic Regression | Sigmoid |
| Multiclass (1 of many) | Logistic Regression | Softmax |
| Multilabel (many per row) | OneVsRestClassifier | Sigmoid |

### 🧠 Memory Trick
- **Sigmoid** → single ON/OFF switch  
- **Softmax** → competition between classes  
- **One-vs-Rest** → multiple binary decisions  

---

## 4️⃣ Which Classification Model to Start With?

| Situation | Start With |
|--------|-----------|
| Small dataset | Logistic Regression |
| Text data | Naive Bayes |
| Complex boundary | SVM |
| Overfitting | Random Forest |
| High accuracy needed | Gradient Boosting |

---

## 5️⃣ Regression Cheat Sheet

### 🔹 Shape of relationship?

| Pattern | Model |
|------|------|
| Straight line | Linear Regression |
| Multiple inputs | Multiple Linear Regression |
| Curve | Polynomial Regression |

---

## 6️⃣ Regularization (When Model Misbehaves)

| Problem | Solution |
|------|---------|
| Overfitting | Ridge Regression |
| Too many features | Lasso Regression |
| Both issues | Elastic Net |

### 🧠 Memory Trick
- **Ridge** shrinks weights  
- **Lasso** removes features  
- **Elastic Net** balances both  

---

## 7️⃣ Tree-Based Models

| Scenario | Model |
|--------|------|
| Simple rules | Decision Tree |
| Overfitting trees | Random Forest |
| Best performance | Gradient Boosting |

---

## 8️⃣ Distance-Based Models

| Situation | Use |
|--------|----|
| Similarity matters | KNN |
| Small dataset | KNN |
| Large dataset | ❌ Avoid KNN |

---

## 9️⃣ Loss Functions

| Task | Loss Function |
|----|--------------|
| Regression | MSE / MAE |
| Classification | Log Loss |
| Probability models | Cross-Entropy |

---

## 🔟 Evaluation Metrics

| Problem | Metric |
|------|------|
| Balanced classification | Accuracy |
| Imbalanced classification | Precision / Recall |
| Regression | RMSE, R² |

---

## 11️⃣ IF YOU SEE → DO THIS (FAST DECISION TABLE)

| You See | You Do |
|------|-------|
| Binary labels | Sigmoid |
| Multiple classes | Softmax |
| Multiple labels | OneVsRest |
| Curved data | Polynomial |
| Noise | Regularization |
| Overfitting | Random Forest |
| Text data | Naive Bayes |
| Need fast baseline | Logistic Regression |

---

## 📂 Recommended Project Structure

