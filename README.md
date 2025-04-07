# 🧹 Data Cleaning: Customer Personality Analysis

This project is a part of a Data Cleaning and Preprocessing Task. The goal was to clean a raw marketing dataset from the Customer Personality Analysis project.

---

## 📁 Dataset Used
**Dataset Name**: Customer Personality Analysis  
**Source**: Kaggle  
**File**: `marketing_campaign.csv`

---

## 🛠 Tools & Libraries Used
- Python
- Pandas
- Jupyter Notebook

---

## 📌 Tasks Performed
- Handled **missing values** using `fillna()`
- Removed **duplicate rows** using `drop_duplicates()`
- Standardized **column names** (lowercase + snake_case)
- Converted **date column** to `datetime` format
- Standardized **categorical values** (like education, marital_status)
- Exported a clean version of the dataset: `marketing_campaign_cleaned.csv`

---

## ✅ Cleaned Dataset Preview

| id   | year_birth | education | marital_status | income  | dt_customer | ... |
|------|-------------|------------|------------------|----------|----------------|-----|
| 5524 | 1957        | graduation | single           | 58138.0 | 2012-09-04     | ... |
| 2174 | 1954        | graduation | single           | 46344.0 | 2014-03-08     | ... |

---

## 📤 How to Run
1. Open the `Task _1_ Data_ Cleaning_ and_ Preprocessing.ipynb` notebook.
2. Run each cell sequentially to clean the dataset.
3. Cleaned CSV will be saved as `marketing_campaign_cleaned.csv`.

---

## 📚 Interview Questions Practiced
1. What are missing values and how do you handle them?
2. How do you treat duplicate records?
3. Difference between `dropna()` and `fillna()` in Pandas?
4. Explain the process of standardizing data.
5. How do you handle inconsistent data formats (e.g., date/time)?

---

## 🚀 Author
**Aryan Zende**  
Aspiring Data Scientist | AI & DS B.Tech | Passionate about Clean Data 🧠  
[LinkedIn](https://www.linkedin.com/in/aryan-zende/)
