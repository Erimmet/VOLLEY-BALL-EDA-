# 🏐 2023 Volleyball Nations League (VNL) — Exploratory Data Analysis

An end-to-end **Exploratory Data Analysis (EDA)** of elite player performance in the 2023 VNL season.  
This project investigates how **position, age, and country** relate to key performance metrics: **Attack, Block, Serve, and Dig**.

---

## 🎯 Objective
- Understand the distribution of core performance metrics  
- Identify relationships between variables (e.g., Attack vs Block/Serve)  
- Compare performance across **countries**, **positions**, and **age groups**  
- Extract actionable insights that explain player performance patterns  

---

## 📂 Dataset
The dataset contains player-level statistics from the 2023 VNL, including:
- **Country**
- **Position** (e.g., OH, OP, S, L)
- **Age**
- **Performance Metrics:** Attack, Block, Serve, Dig  

> (https://www.kaggle.com/datasets/yeganehbavafa/vnl-men-2023)

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook  

---

## 🔍 Analysis Overview

### 1. Data Cleaning & Preparation
- Checked for missing values and duplicates  
- Verified data types and overall structure  

### 2. Univariate Analysis
- Histograms and boxplots to examine distributions and detect outliers  
- Assessed spread and skewness of performance metrics  

### 3. Bivariate Analysis
- Correlation heatmap to explore pairwise relationships  
- Scatter plots to examine relationships (e.g., **Attack vs Block**)  

### 4. Multivariate Analysis
- Grouped analysis by **Country**, **Position**, and **Age**  
- Compared average performance across multiple dimensions  

---

## 📊 Key Insights

- **Positional Specialization:**  
  Offensive roles (e.g., **Outside Hitters (OH)**, **Opposites (OP)**) tend to record higher **Attack** values, while **Liberos (L)** and **Setters (S)** contribute more in defensive/facilitation metrics.

- **Performance Relationships:**  
  A strong positive correlation (**≈ 0.77**) exists between **Attack** and **Serve**, suggesting that players who excel in attacking often also perform well in serving.

- **Country-Level Patterns:**  
  Some countries consistently show higher averages across multiple metrics.  
  *For example:* **France** appears among the more balanced teams, performing strongly in both offensive and defensive measures.

- **Age Trends:**  
  Performance remains relatively stable across the **20–35 age range**, indicating that experience may offset physical decline within this dataset.

---

## 📈 Visualizations Included
- **Histograms & Boxplots:** Distribution and outlier detection  
- **Correlation Heatmap:** Relationships between performance metrics  
- **Scatter Plots:** Key variable relationships (e.g., Attack vs Block)  
- **Bar Charts:** Comparative analysis by Country and Position  
- **Line Plots:** Trends across Age  

---

## 🏁 Conclusion
The analysis highlights that elite volleyball performance is strongly influenced by **role specialization** and **team composition**.  
Offensive output is driven by key attacking positions, while defensive stability depends on specialized roles.  

Additionally, performance patterns suggest that:
- Core skills (Attack, Serve) are often linked  
- Team-level success may come from balanced contributions across multiple metrics  
- Experience plays a meaningful role alongside physical performance  


---

## 📌 Future Improvements
- Apply statistical tests to validate observed trends  
- Build predictive models for player performance  
- Incorporate additional features (e.g., match context, team tactics)  

---

## 🤝 Acknowledgment
This project is part of a hands-on journey in **Data Analysis and Machine Learning**, focusing on turning raw data into meaningful insights.
