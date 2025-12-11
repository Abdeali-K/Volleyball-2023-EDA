# Volleyball-2023-EDA
# 🏐 Volleyball Nations League (VNL) 2023 – Exploratory Data Analysis

This project performs an **Exploratory Data Analysis (EDA)** on the **VNL 2023 (Men/Women) Volleyball dataset**.  
The goal is to understand how teams performed across various statistical categories such as **Attack, Block, Serve, Dig, Set, and Reception**, and extract meaningful insights through visualizations.

---

## 📂 Project Structure
VNL2023-EDA/
│── Volleyball.ipynb # Jupyter notebook containing full analysis
│── VNL2023.csv # Dataset used for EDA
│── README.md # Project documentation


---

## 📊 Objectives of the Analysis
The notebook focuses on:

### **1. Data Loading & Cleaning**
- Loaded the VNL 2023 dataset using Pandas  
- Checked missing values  
- Displayed basic structure of the dataset (head, tail, info, etc.)

### **2. Statistical Summary**
- Used `describe()` to understand data distribution  
- Checked numerical features (Attack, Block, Serve, etc.)  

### **3. Exploratory Data Analysis**
The notebook contains multiple visualizations, including:

#### ✔ Distribution Plots
- Attack score distribution  
- Block score distribution  
- Serve score distribution  
- Dig, Set, and Reception distributions  

#### ✔ Country-Level Performance Analysis
- Total Attack and Block points grouped by country  
- Sort and compare highest/lowest performing teams  
- Visualized using Matplotlib & Seaborn bar plots  

#### ✔ Correlation Analysis
- Generated a correlation heatmap  
- Identified relationships between volleyball skills and match outcome patterns  

---

## 📈 Key Insights
Some general insights your notebook explores:

- Which countries dominate **Attack**, **Block**, or **Serve** categories  
- How different statistical categories correlate with each other  
- Patterns of performance across countries  
- Understanding distribution skewness of performance metrics  

*(You can add exact findings here once you finalize results.)*

---

## 🛠️ Technologies Used
- **Python**
- **Pandas** for data manipulation  
- **Matplotlib & Seaborn** for visualizations  
- **Jupyter Notebook** for interactive analysis  

---

## 🚀 How to Run
1. Clone the repository:
```bash
git clone https://github.com/your-username/vnl2023-eda.git
