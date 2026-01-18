# 📊 Exploratory Data Analysis (EDA) of Shoes Sales

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on a shoes sales dataset using Python.  
The goal is to analyze sales trends, apply statistical techniques, detect outliers, handle missing values, and compare **Nike vs Adidas** sales performance.

---

## 🎯 Objectives
- Understand shoes sales distribution
- Perform brand-wise analysis (Nike & Adidas)
- Apply statistical measures (mean, median, percentiles)
- Detect and treat outliers
- Visualize daily sales trends

---

## 🛠️ Tools & Technologies
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook**

---

## 📂 Dataset Description
The dataset contains daily sales records with the following columns:

| Column | Description |
|------|------------|
| `date` | Sales date |
| `brand` | Shoe brand (Nike / Adidas) |
| `sold_qty` | Quantity of shoes sold |

---

## 🔍 Analysis Workflow

### 1️⃣ Data Exploration
- Loaded CSV data
- Checked shape and structure
- Generated statistical summary

📸 **Dataset Overview**
![Dataset Overview](images/dataset_overview.png)

---

### 2️⃣ Statistical Analysis
- Calculated **mean, median, and percentiles**
- Identified lower and upper bounds for sales
- Compared brand-wise statistics

---

### 3️⃣ Nike vs Adidas Sales (Before Outlier Handling)
- Visualized daily sales trends
- Identified abnormal spike in Adidas sales

📸 **Sales Before Outlier Handling**
![Before Outlier](images/nike_adidas_before_outlier.png)

---

### 4️⃣ Outlier Detection
- Used **percentile method (IQR logic)**
- Detected extreme Adidas sales values

📸 **Outlier Detection**
![Outlier Detection](images/outlier_detection.png)

---

### 5️⃣ Outlier Treatment
- Replaced outlier values using **median**
- Prevented skewing of analysis

---

### 6️⃣ Final Sales Trend (After Outlier Handling)
- Cleaned and stabilized dataset
- Compared Nike and Adidas sales again

📸 **Sales After Outlier Handling**
![After Outlier](images/nike_adidas_after_outlier.png)

---

## 📌 Key Insights
- Nike shows more **consistent daily sales**
- Adidas had extreme values affecting trends
- Median-based replacement improved data quality
- Visualization helped clearly compare brand performance

---

## ▶️ How to Run the Project

```bash
git clone https://github.com/your-username/EDA-Shoes-Sales.git
cd EDA-Shoes-Sales
pip install -r requirements.txt
jupyter notebook
