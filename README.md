# Logistic Regression - Breast Cancer Classification

## 📌 Overview
Binary classification using **Logistic Regression** on the **Breast Cancer Wisconsin Dataset**.  
Objective: Predict whether a tumor is **Malignant (1)** or **Benign (0)**.

---

## ⚙️ Steps Performed
1. Load dataset (`load_breast_cancer` from scikit-learn).
2. Split data (80% training, 20% testing).
3. Standardize features with `StandardScaler`.
4. Train Logistic Regression (`liblinear` solver).
5. Evaluate with:
   - Confusion Matrix
   - Precision, Recall, F1-score, Accuracy
   - ROC-AUC score
6. Visualize:
   - ROC Curve
   - Confusion Matrix heatmap
7. Tune thresholds for Recall vs Precision tradeoff.

---

## 📊 Results
- **Accuracy:** ~96%  
- **Precision:** ~0.97  
- **Recall:** ~0.93  
- **F1-score:** ~0.95  
- **ROC-AUC:** ~0.98  

---

## 📷 Sample Outputs
### ROC Curve
![ROC Curve](roc_curve.png)

### Confusion Matrix
![Confusion Matrix](confusion_matrix.png)

---

## 💡 Key Learnings
- Logistic Regression is simple yet effective for classification tasks.
- Accuracy alone isn’t enough; **precision, recall, and AUC** give deeper insight.
- **Threshold tuning** adjusts trade-off between false positives and false negatives.
- Logistic Regression can also handle **multi-class classification** using OvR or Softmax.

---

## 🚀 How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/Logistic-Regression-Task.git
   cd Logistic-Regression-Task
