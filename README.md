# 🤖 ML Mini Projects

Chhote, beginner-friendly Machine Learning projects — real datasets, clean code, har step ke saath explanation. Ye projects **AI/ML Club interview prep** ke liye banaye gaye hain, do alag ML paradigms cover karte hain: Regression aur Clustering.

---

## 📁 Projects

### 1️⃣ Diabetes Progression Prediction — *Regression*

Patient ke health measurements (age, BMI, blood pressure, etc.) se disease progression score predict karta hai.

| | |
|---|---|
| **Type** | Supervised Learning – Regression |
| **Algorithm** | Linear Regression |
| **Dataset** | `sklearn.datasets.load_diabetes` (442 samples, 10 features) |
| **File** | [`diabetes_prediction.ipynb`](./diabetes_prediction.ipynb) |

**Steps covered:** data loading → data cleaning (null/duplicate check) → train-test split → model training → evaluation (MSE, RMSE, MAE, R²) → visualization

---

### 2️⃣ Customer Segmentation — *Clustering (Unsupervised)*

Mall customers ko unke annual income aur spending score ke basis pe groups mein baantta hai.

| | |
|---|---|
| **Type** | Unsupervised Learning – Clustering |
| **Algorithm** | K-Means Clustering |
| **Dataset** | Mall Customers Dataset (real, 200 customers) — [`Mall_Customers.csv`](./Mall_Customers.csv) |
| **File** | [`cluster_.ipynb`](./cluster_.ipynb) |
| **Result** | 5 customer segments identified (Target Customers, Careful Rich, Impulsive, Careful Spenders, Average) |

**Steps covered:** data loading → data cleaning → feature scaling → Elbow Method (best K finding) → K-Means clustering → cluster interpretation → visualization

---

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/YOUR-USERNAME/ml-mini-projects.git
cd ml-mini-projects

# Install dependencies
pip install -r requirements.txt

# Open notebooks in Jupyter
jupyter notebook
```

Note: `Mall_Customers.csv` must stay in the same folder as `cluster_.ipynb` — the notebook reads it directly.

---

## 🧠 Concepts Practiced

- Supervised vs Unsupervised Learning
- Data cleaning (missing values, duplicates)
- Train-test split & feature scaling
- Linear Regression, K-Means Clustering
- Evaluation metrics: MSE, RMSE, MAE, R², Inertia
- Elbow Method for choosing optimal clusters
- Cluster interpretation & business insights
- Data visualization with Matplotlib

---

## 🛠️ Built With

- Python 3
- [scikit-learn](https://scikit-learn.org/)
- pandas
- numpy
- matplotlib

---

## 📌 Dataset Credit

Mall Customer Segmentation dataset sourced from Kaggle — widely used dataset for learning clustering fundamentals.

---

## 📌 Note

These are learning/practice projects built for ML fundamentals — meant to demonstrate understanding of the end-to-end ML workflow.
