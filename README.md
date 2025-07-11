# Walmart Sales EDA & Data Cleaning 🛒

This project focuses on analyzing and cleaning Walmart's **weekly sales dataset**, preparing it for further modeling or forecasting.

---

## 📌 Objectives

- Perform Exploratory Data Analysis (EDA)
- Clean the dataset and handle outliers
- Convert and extract time-based features from dates
- Save a cleaned version for future modeling

---

## 🧪 Dataset

- Source: `Walmart.csv`
- Size: Over multiple stores and weekly sales data
- Columns: `Store`, `Date`, `Weekly_Sales`, `Holiday_Flag`, `Temperature`, `Fuel_Price`, `CPI`, `Unemployment`

---

## 🔍 Exploratory Data Analysis

### 🛠️ Key Steps:

- Checked for missing and duplicated values
- Count of unique dates
- Visualized correlation matrix using heatmap
- Count of holidays using bar plot
- Boxplot to detect outliers in `Weekly_Sales`

---

## 🧼 Data Cleaning

- Converted `Date` column to datetime format
- Extracted:
  - `Year` and `Month` from date
- Detected and removed outliers in `Weekly_Sales` using **IQR method**
- Planned saving cleaned dataset:  

df.to_csv("cleaned_walmart_data.csv", index=False)


🔮 Future Work
Forecasting sales using Time Series models

Analyzing impact of holidays on revenue

🛠️ Tools & Libraries
pandas
numpy
matplotlib
seaborn
missingno

👨‍💻 Author
Ahmed Osama – Data Science Learner
