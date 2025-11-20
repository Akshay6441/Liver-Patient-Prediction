# Liver-Patient-Prediction
# 🧠 Liver Patient Prediction – Machine Learning Project

## 📌 Project Overview  
This project predicts whether a person is likely to have **liver disease** based on medical parameters using **machine learning**. It is a **binary classification** problem (`disease` / `no disease`) implemented using Python and Jupyter Notebook.

The project focuses on:
- Understanding liver disease data  
- Cleaning & preprocessing the data  
- Training multiple ML models  
- Comparing model performance  
- Selecting the best model  

---

## 📂 Dataset Information  

| Detail | Description |
|-------|-------------|
| Dataset Name | Indian Liver Patient Dataset (ILPD) |
| Source | UCI Machine Learning Repository / Kaggle |
| Records | 583 instances |
| Features | 10 input features + 1 target column |
| Target | Liver Disease = 1, No Disease = 0 |

### 🔑 Attributes Used:
- Age  
- Gender  
- Total Bilirubin  
- Direct Bilirubin  
- Alkaline Phosphatase  
- SGPT (Alanine Aminotransferase)  
- SGOT (Aspartate Aminotransferase)  
- Total Proteins  
- Albumin  
- Albumin/Globulin Ratio  

---

## ⚙️ Tech Stack Used

| Component | Tools / Libraries |
|-----------|--------------------|
| Language | Python 3.x |
| Notebook | Jupyter Notebook |
| Libraries | NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn |
| IDE Used | Jupyter Notebook / VS Code |

---

## 🧠 ML Workflow / Methodology

```
Dataset → Data Cleaning → Feature Engineering → Train/Test Split  
            ↓  
Apply ML Algorithms (Logistic Regression, Random Forest, SVM, etc.)  
            ↓  
Evaluation → Best Model Selection  
```

---

## 🚀 How to Run the Project

1️⃣ Upload the Notebook

Go to:
https://colab.research.google.com/

→ Click Upload
→ Select Liver_Patient_Prediction.ipynb

2️⃣ OR Open Directly from GitHub

In Google Colab → File → Open Notebook → GitHub Tab
Paste:

https://github.com/Akshay6441/Liver-Patient-Prediction

3️⃣ Install Dependencies
pip install numpy pandas scikit-learn matplotlib seaborn

4️⃣ Run All Cells

Click Runtime → Run all
---

## 📁 Project Structure

```
Liver-Patient-Prediction/
│
├── notebooks/
│   └── Liver_Patient_Prediction.ipynb      ← main ML code
│
├── data/
│   └── liver_data.csv                       ← dataset (optional)
│
├── README.md                                ← this file
└── requirements.txt                         ← optional library list
```

---

## 📊 Model Comparison (Example Results)

| Model | Accuracy | F1-score |
|------|---------|-----------|
| Logistic Regression | 78% | 0.72 |
| Decision Tree | 82% | 0.78 |
| **Random Forest (Best)** | **85%** | **0.81** |
| SVM | 83% | 0.79 |

✔ Final selected model: **Random Forest**

---

## 🔍 Key Observations
- Dataset is slightly imbalanced → Stratified split used  
- Removing missing values improved model stability  
- Random Forest gave best balance between **accuracy** and **recall**  
- Medical projects must prioritize **recall** (to detect patients early)  


---

## 📌 Disclaimer  
This project is for **educational and research purposes only**.  
It does **not** serve as medical advice or diagnosis.

