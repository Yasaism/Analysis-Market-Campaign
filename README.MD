# 📊 ASOS Product Data Analysis

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview
This project focuses on data preprocessing and initial analysis of ASOS product data. The primary objective is to clean raw data, extract meaningful features (such as brand information), and prepare the dataset for further analytical or machine learning tasks.

---

## ⚙️ Workflow

### 1. Data Loading
- Load dataset from CSV file  
- Handle malformed rows using safe parsing  

### 2. Data Cleaning
- Convert `price` column to numeric format  
- Remove invalid or missing price values  

### 3. Data Preparation
- Standardize text data in the `description` column  
- Ensure compatibility for text processing  

### 4. Feature Engineering
- Extract brand names from product descriptions  
- Create a new feature: `brand_raw`  

---

## 🧪 Technologies Used
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**

---

## 📂 Project Structure
```
.
├── data/
│   └── products_asos.csv
├── notebooks/
│   └── product_asos.ipynb
├── README.md
└── requirements.txt
```

---

## 🔍 Key Insights

### ✅ Strengths
- Clear and structured data processing pipeline  
- Efficient handling of invalid numeric values  
- Custom feature extraction from unstructured text  

### ⚠️ Limitations
- Skipping malformed rows may result in silent data loss  
- Brand extraction method is simplistic and may miss variations  
- No explicit tracking of removed or missing data  
- Limited exploratory data analysis (EDA)  

---

## 🚀 Future Improvements
- Implement robust text extraction using regular expressions  
- Add data validation and logging mechanisms  
- Perform exploratory data analysis (EDA) and visualization  
- Extend to machine learning models (e.g., price prediction, clustering)  

---

## ▶️ How to Run

1. Clone this repository:
```bash
git clone https://github.com/your-username/asos-product-analysis.git
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the Jupyter Notebook:
```bash
jupyter notebook notebooks/product_asos.ipynb
```

---

## 📊 Example Output
- Cleaned dataset with valid pricing  
- Extracted brand information  
- Ready-to-use structured data for analysis  

---

## 🧠 Conclusion
This project provides a solid foundation for data preprocessing and feature engineering on e-commerce datasets. It can be further enhanced with deeper analytical techniques and machine learning integration.
