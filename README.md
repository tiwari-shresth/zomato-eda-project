# 🍽️ Zomato Dataset - Exploratory Data Analysis (EDA)

This project explores the Zomato restaurant dataset using Python to uncover insights into cuisines, ratings, costs, and country-level restaurant trends. It also merges external country codes for a complete picture.

---

## 🔍 Analysis Focus

1. Handling **missing values**
2. Exploring **numerical** & **categorical** variables
3. Understanding **rating distributions**
4. Analyzing **cuisine popularity**
5. Cost & availability of **online food orders**
6. Country-wise breakdown of restaurant data

---

## 📊 Key Insights from the Dataset

- 🇮🇳 **India** has the highest number of restaurant records.
- 🍽️ **Top 5 most common cuisines**:
  - North Indian  
  - North Indian, Chinese  
  - Chinese  
  - Fast Food  
  - North Indian, Mughlai

- 🌟 **Ratings Distribution**:
  - Most ratings lie between **3.0 to 4.0**
  - Over **2,100+ restaurants are unrated (0.0)**

- 🛵 **Online Order Availability**:
  - **Yes**: 2,451 restaurants  
  - **No**: 7,100 restaurants  
  - 📌 _Observation_: Online delivery is only available in **India** and **UAE**

- 💰 **Cost for Two** (local currency):
  - **Mean**: ₹1,199  
  - **Median**: ₹400  
  - **Common range**: ₹250 – ₹700  
  - **Max**: ₹800,000 _(outlier)_

---

## 🛠️ Tools & Libraries Used

- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn

---

## 📂 Files Included

- `Zomato Dataset EDA.ipynb` – Full EDA notebook
- `zomato.csv` – Raw dataset with restaurant details
- `Country-Code.xlsx` – Mapping of country codes to country names

---

## 📓 How to Run

1. Clone this repository
2. Open the notebook `Zomato Dataset EDA.ipynb`
3. Install dependencies:
   ```bash
   pip install pandas matplotlib seaborn openpyxl