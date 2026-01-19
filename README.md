
# 💳 Credit Card Fraud Detection using Machine Learning

## 🔍 Overview
This project aims to detect fraudulent credit card transactions using machine learning techniques. It leverages an imbalanced dataset and applies various preprocessing, visualization, and modeling strategies to improve fraud classification accuracy.

## 🧠 Tech Stack
- **Language:** Python  
- **Notebook:** Jupyter (Google Colab-compatible)  
- **Libraries:**  
  - `pandas`, `numpy` – Data handling  
  - `matplotlib`, `seaborn` – Visualization  
  - `scikit-learn` – ML models (Logistic Regression, Decision Trees, etc.)  
  - `imbalanced-learn` – Handling class imbalance (SMOTE)

## 📁 Project Structure

```
Credit_Card_Fraud_Detection_ML/
│
├── Credit_Card_Fraud_Detection_(mini_proj).ipynb   # Main notebook
├── report.pdf                                      # Report document

```

## 📊 Dataset
- **Source:** [Kaggle Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- **Description:** Contains transactions made by European cardholders in September 2013. Out of 284,807 transactions, 492 are fraudulent.
- **Features:** Numerical features (`V1` to `V28` from PCA), `Amount`, `Time`, and binary `Class` (1 = fraud, 0 = legit)

## 📈 Workflow Summary

1. **📂 Load & Explore Data**
   - Handled large, imbalanced dataset
   - Visualized fraud-to-legit transaction ratio

2. **🧹 Preprocessing**
   - Handled missing values and scaled numerical features
   - Applied SMOTE to balance the dataset

3. **🧪 Modeling**
   - Trained and evaluated multiple models:
     - Logistic Regression ✅
     - Decision Tree Classifier 🌳
     - Random Forest Classifier 🌲
     - K-Nearest Neighbors 👥

4. **📊 Evaluation Metrics**
   - Accuracy, Precision, Recall, F1-score
   - Confusion matrix and ROC-AUC analysis

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
   ```

2. Open the notebook on Google Colab:
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Vrishin-Reddy/Mini_Proj/blob/master/Credit_Card_Fraud_Detection_(mini_proj).ipynb)

3. Run all cells to reproduce results and visuals.

## 📌 Key Highlights
- Addressed class imbalance using SMOTE
- Demonstrated feature importance & visualization
- Compared multiple ML models for fraud detection

## 📄 Report
For in-depth methodology, results, and analysis, refer to:  
📘 `report.pdf`


