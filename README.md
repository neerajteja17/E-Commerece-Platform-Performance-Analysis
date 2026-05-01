# 📊 E-Commerce Platform Performance Analysis

## 📌 Project Overview
This project analyzes the performance of e-commerce platforms using a real-world Brazilian marketplace dataset. The goal is to understand how delivery performance, pricing, and product categories impact customer satisfaction and sales trends.

---

## 🎯 Problem Statement
How do delivery performance and product categories influence customer satisfaction and sales trends in a multi-state marketplace?

---

## 🚀 Objectives
- Analyze customer purchasing behavior  
- Identify delivery bottlenecks  
- Evaluate product pricing and shipping cost relationships  
- Determine high-performing regions and categories  
- Visualize sales trends and patterns  

---

## 📂 Dataset
Dataset used: **Brazilian E-Commerce Dataset (Olist)**  

### Key Tables:
- **Customers Dataset**
  - Customer ID, City, State
- **Orders Dataset**
  - Order status, timestamps, delivery details
- **Order Items Dataset**
  - Product ID, price, freight value

### Relationships:
- Customers → Orders → Order Items  
- One customer → multiple orders  
- One order → multiple items  

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 🔄 Project Workflow

### 1. Data Collection
- Dataset imported from Kaggle using `kagglehub`

### 2. Data Cleaning & Wrangling
- Datatype conversion (timestamps)
- Missing value handling
- String cleaning
- Duplicate removal
- Filtering & sorting
- Data reshaping (pivot, stack, unstack)

### 3. Data Analysis
- Summary statistics (mean, median, std deviation)
- Revenue analysis by state  
- Feature scaling (Z-score normalization)
- Outlier detection using IQR method  

### 4. Data Visualization

#### 📈 Matplotlib
- Monthly sales trend  
- Top 10 cities by order volume  
- Price vs freight scatter plot  

#### 📊 Seaborn
- Orders by day of week  
- Correlation heatmap  
- Price distribution by state  
- Freight distribution (violin plot)  
- Pairplot analysis  

---

## 📊 Key Insights
- Highest revenue generated from states like **SP, RJ, MG**  
- Mid-week shows peak order activity  
- Moderate correlation between price and freight cost  
- Outliers significantly impact average pricing  
- Sales trend shows steady growth with fluctuations  

---

## 📌 Results
- Mean price reduced after removing outliers (≈120 → ≈84)  
- Clear regional differences in revenue  
- Strong patterns observed in customer ordering behavior  

---

## ▶️ How to Run

```bash
# Clone repository
git clone <your-repo-link>

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn kagglehub

# Run notebook
jupyter notebook
