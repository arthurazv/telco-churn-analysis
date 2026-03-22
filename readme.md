# 📊 Telco Customer Churn Analysis & Prediction

This project focuses on **Exploratory Data Analysis (EDA)** and **Machine Learning modeling** to understand and predict customer churn behavior using the Telco dataset.

---

## 🚀 Objectives

- Perform data cleaning and preprocessing
- Analyze customer behavior through EDA
- Identify key factors related to churn
- Build a predictive model for churn classification

---

## 📁 Dataset

The dataset contains **7043 customers** with **33 variables**, including:

- Demographics (gender, age, location)
- Account information (tenure, contract type)
- Services (internet, phone, streaming)
- Financial data (monthly and total charges)
- Target variable: **Churn**

---

## 🔍 Project Structure

```
.
├── data/
│   └── Telco_customer_churn.xlsx
├── 01-eda & model.ipynb
└── README.md
```

---

## 🧪 Exploratory Data Analysis (EDA)

Key steps performed:

- Data inspection (`head`, `info`, `describe`)
- Handling missing values (e.g., `Total Charges`)
- Feature classification:
  - Numerical (discrete & continuous)
  - Categorical (nominal)

- Distribution analysis:
  - Histograms
  - Boxplots

- Categorical insights

### 📌 Key Insights

- Balanced gender distribution (~50% male)
- Low percentage of senior citizens (~16%)
- Strong relationship between:
  - Contract type and churn
  - Monthly charges and churn
  - Tenure and churn

---

## 🤖 Machine Learning

The project includes:

- Train/test split using `scikit-learn`
- Feature preparation
- Model training (classification)

> (You can expand here with the exact model you used: Logistic Regression, Random Forest, etc.)

---

## 🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/arthurazv/telco-churn-analysis
cd telco-churn-analysis
```

2. Install dependencies:

```bash
pip install pandas matplotlib seaborn scikit-learn openpyxl
```

3. Run the notebook:

```bash
jupyter notebook
```

---

## 📈 Future Improvements

- Hyperparameter tuning
- Feature engineering
- Model comparison
- Deployment (API or dashboard)

---

## 👨‍💻 Author

Arthur Azevedo

---

## 📄 License

This project is for educational purposes.
