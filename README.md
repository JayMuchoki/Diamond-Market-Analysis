# 💎 Diamond Price Analysis - Seaborn Dataset

This project explores the popular **diamonds** dataset available in Seaborn. The primary goal is to analyze various features of diamonds and their influence on pricing. Through data preprocessing, visualization, and statistical analysis, the project uncovers insights that help in understanding the factors that drive diamond prices.

---

## 📌 Project Objectives

- Perform data cleaning and preparation  
- Explore and visualize trends in diamond pricing  
- Identify the most influential features affecting price  
- Demonstrate skills in Python data analysis and storytelling  

---

## 📂 Dataset Overview

The dataset contains over 50,000 observations of diamonds with the following key features:

- **carat**: weight of the diamond (0.2–5.01)  
- **cut**: quality of the cut *(Fair, Good, Very Good, Premium, Ideal)*  
- **color**: diamond color *(from J - worst to D - best)*  
- **clarity**: measurement of how clear the diamond is *(I1 - worst to IF - best)*  
- **depth**: total depth percentage  
- **table**: width of the top of the diamond relative to the widest point  
- **price**: price in US dollars  
- **x, y, z**: length, width, and depth in mm  

---

## 🛠️ Technologies Used

- Python 3.10+  
- Pandas – Data manipulation and analysis  
- NumPy – Numerical operations  
- Seaborn & Matplotlib – Data visualization  
- Jupyter Notebook – Interactive analysis environment  
- PowerPoint – Project presentation  

---

## 📊 Key Analysis Performed

### 1. 🧹 Data Cleaning
- Checked for null or missing values  
- Removed invalid entries with zero values in `x`, `y`, or `z` dimensions  

### 2. 📈 Exploratory Data Analysis (EDA)
- Distribution plots of diamond prices  
- Count plots for `cut`, `color`, and `clarity`  
- Scatter plots: `price` vs. `carat`, colored by `clarity` and `cut`  
- Box plots comparing price distributions by `cut` and `color`  
- Correlation heatmaps to understand feature relationships  

### 3. 📌 Key Insights
- **Carat** has the strongest positive correlation with price  
- **Premium** and **Ideal** cuts dominate the dataset  
- Diamonds with better **clarity** and **color** command higher prices  
- Price outliers exist and were identified visually  

---

## 📁 Project Structure

diamond-price-analysis/
│
├── data/                   # Raw or cleaned datasets
│   └── diamonds.csv
│
├── notebooks/              # Jupyter Notebooks for analysis
│   └── diamond_analysis.ipynb
│
├── images/                 # Saved visualizations
│   ├── price_vs_carat.png
│   └── correlation_heatmap.png
│
├── scripts/                # (Optional) Reusable Python scripts/functions
│   └── utils.py
│
├── output/                 # Final reports, summaries, or exports
│   └── summary.csv
│
├── README.md               # Project overview and documentation
├── requirements.txt        # Python dependencies
├── .gitignore              # Files/folders to exclude from version control
└── LICENSE                 # License file (optional)
