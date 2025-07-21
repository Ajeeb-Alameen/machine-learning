
# 🧠 Classification Projects

## 📌 Overview

This folder contains multiple classification-focused machine learning projects using real-world data to solve business and security problems. The projects apply a variety of classification algorithms including `K-Nearest Neighbors`, `Logistic Regression`, `Decision Trees`, `SVM`, `Random Forest`, `and deep learning FeedForward Neural Network`(**FFNN**). Each project highlights the workflow from EDA to final model evaluation.

---

## 📁 Folder Structure

```
Classification_projects/
├── Detecting Cyber Security Threats using Deep Learning/
│   └── notebook.ipynb + data
│
├── Indian Telecom Customer Churn Prediction/
│   └── notebook.ipynb + data
│
├── classification_project/
│   └── Predicting Heart Disease.ipynb + data
│
└── README.md
```

> 📁 Each subfolder contains:
> - A notebook (`.ipynb`)
> - With its relevant datasets
> - Commented code for reproducibility and analysis
---

## 🧪 Included Projects

### 🔐 Detecting Cyber Security Threats using Deep Learning
- **Goal**: Classify network traffic as benign or malicious.
- **Dataset**: Preprocessed network event logs.
- **Highlights**:
  - Implemented a PyTorch feedforward neural network.
  - Addressed class imbalance using weighted loss.
  - Applied dropout and early stopping to prevent overfitting.
  - Visualized ROC and Precision-Recall curves.
  - Achieved very high recall with low false positives; precision can be improved with further tuning

### 📞 Indian Telecom Customer Churn Prediction
- **Goal**: Predict churn using user demographics and behavior.
- **Dataset**: Telecom usage + customer profile.
- **Highlights**:
  - Feature engineering on categorical and usage features.
  - Used SMOTE to address class imbalance.
  - Compared multiple models (Logistic Regression, SVM, Random Forest).
  - Logistic Regression offered the best trade-off between recall and precision for churn detection.

### ❤️ Predicting Heart Disease
- **Goal**: Predict heart disease diagnosis based on health indicators.
- **Dataset**: UCI Heart Disease dataset (`heart.csv`).
- **Highlights**:
  - Data normalization and train/test split.
  - Evaluated KNN, Logistic Regression, Decision Tree Classifier.
  - Visual analysis: Confusion Matrix, ROC Curve.
  - Decision Tree achieved the best AUC and balanced accuracy, making it the top choice.
---

## 🛠 Technologies Used

- **Language**: `Python`
- **Tools & Libraries**:
  - `pandas`, `numpy`, `matplotlib`, `seaborn`
  - `Scikit-Learn`, `PyTorch` (for DL project)
- **Environment**: `Jupyter Notebook`

---

## 🚀 How to Run

1. **Clone the repo**
   ```bash
   git clone https://github.com/Ajeeb-Alameen/Machine_learning.git
   cd Machine_learning/Classification_projects
   ```

2. **Launch any notebook**
   ```bash
   jupyter notebook <notebook_name>.ipynb
   ```

---

## ✅ Future Enhancements

- Use cross-validation and grid search for model tuning.
- Apply XGBoost or ensemble methods for better performance.

---

## 🔗 Links

- 📂 GitHub Repository: [Machine Learning Repo](https://github.com/Ajeeb-Alameen/Machine_learning)
- ✍ Author: Ajeeb Alameen
- 📧 Email: ajeebizzalameen@gmail.com
- 🔗 LinkedIn: [Ajeeb Alameen](https://www.linkedin.com/in/ajeeb-alameen)

---
