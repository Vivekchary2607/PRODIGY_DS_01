# 🧠 PRODIGY_DS_01 – Task 01: Data Visualization

## 📌 Task Description
**Objective**: Create a bar chart or histogram to visualize the distribution of a categorical or continuous variable — such as age or gender — in a population.

---

## 📁 Dataset Used

**Dataset**: `global_cancer_patients_2015_2024.csv`  
**Records**: ~50,000 entries  
**Features**:
- **Categorical**: Gender, Cancer_Type, Country_Region, Cancer_Stage
- **Numerical**: Age, Alcohol_Use, Smoking, Obesity_Level, etc.

---

## 📊 Techniques Applied

To uncover patterns and feature distributions in the dataset, I applied various **visualization techniques**:

- ✅ **Histogram** for continuous variable:
  - **Age Distribution** of cancer patients.
- ✅ **Bar Chart** for categorical variable:
  - **Gender Distribution** of patients.
- ✅ Additional exploratory plots for:
  - `Cancer_Stage` distribution
  - `Country_Region` wise patient count
  - `Alcohol_Use` and `Smoking` habits

These plots helped identify demographic trends, risk patterns, and relationships between features.

---

## 🛠️ Libraries Used

- `pandas` – Data loading and preprocessing  
- `numpy` – Numerical computations  
- `matplotlib` – Base plotting library  
- `seaborn` – Enhanced statistical visualizations (for optional styling)

---

## 📌 Summary

> By visualizing key aspects of the cancer patient dataset, I gained insights into how variables like **age**, **gender**, **cancer stage**, and **lifestyle factors** (alcohol use, smoking) are distributed.  
>
> This step is essential in any data science workflow as it helps build intuition about the data and prepares the ground for deeper analysis or model development.

---

## 📷 Visual Outputs

- 📉 **Age Histogram** with KDE Curve  
- 🧍 **Gender Bar Chart**  
- 🌍 Country-level patient counts  
- 📦 Stage-wise cancer distribution  

---

## ✅ Outcome

- Clear understanding of patient demographics  
- Identification of skewed distributions and feature imbalances  
- Foundation for further steps like feature engineering or predictive modeling

---

