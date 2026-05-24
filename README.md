**# winequality-prediction**# 🍷 Wine Quality Prediction using Machine Learning (SVM)

This project predicts whether a wine is of **good or bad quality** using its physicochemical properties with a Support Vector Machine (SVM) model.

---

## 📌 Project Objective

To classify wine quality into two categories:

- **0 → Bad Quality Wine**
- **1 → Good Quality Wine**

based on chemical features of the wine.

---

## 📊 Dataset Information

- Source: UCI Wine Quality Dataset
- Type: White Wine Dataset
- Total Records: 4,898
- Features: 11 physicochemical attributes
- Target: Wine Quality Score (converted into binary classification)

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Support Vector Machine (SVC)
- StandardScaler

---

## 🔄 Project Workflow

1. Load dataset from CSV URL
2. Explore and understand data distribution
3. Check for missing values (none found)
4. Standardize features using StandardScaler
5. Convert target variable into binary classes:
   - 0 → Bad Wine (quality < 6)
   - 1 → Good Wine (quality ≥ 6)
6. Split data into training and testing sets
7. Train SVM classifier
8. Evaluate model performance

---

## 🤖 Machine Learning Model

- Algorithm: Support Vector Machine (SVM)
- Type: Binary Classification
- Kernel: Default (RBF)

---

## 📈 Model Performance

- Accuracy: ~78%

### Evaluation Metrics:
- Confusion Matrix
- Precision
- Recall
- F1-score

---

## 🧪 Prediction Example

The trained model predicts wine quality as:

- **0 → Bad Quality Wine**
- **1 → Good Quality Wine**

Example output:
Prediction: Good Wine (1)
