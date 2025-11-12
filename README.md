# 🧠 Customer Segmentation Team Project

## 👥 Team Members  
- **Project Guided by:** [RD Group of Industries](https://github.com/TheRDGroupOfIndustries)  
- **Siddhesh:** [@siddheshDA](https://github.com/siddheshDA)  
- **Nandini:** [@nandiniarjun03](https://github.com/nandiniarjun03)  
- **Himanshu:** [@Himanshu76-DA](https://github.com/Himanshu76-DA)  

---

## 🧩 Project Overview  

This project focuses on **Customer Segmentation** using **RFM (Recency, Frequency, Monetary) analysis**, supported by **Exploratory Data Analysis (EDA)** and **data cleaning**.  
The goal is to identify valuable customer groups, analyze their purchasing patterns, and extract actionable business insights to improve customer retention and marketing strategies.  

---

## 🔹 Data Cleaning  
**Performed by:** [Siddhesh](https://github.com/siddheshDA)  

### 🧼 Key Steps:
- Handled missing and null values  
- Removed duplicates and fixed incorrect data types  
- Created new features such as **Order Date**, **Order Time**, **Approval Date & Time**, and **Delivered Date & Time**  
- Produced a clean dataset ready for EDA and clustering  

**📂 Files:**  
- [Cleaned Dataset](https://github.com/Himanshu76-DA/Customer-segmentation-team-project-/blob/main/Olis_Order_Dataset(EDA).zip.zip)  
- [Data Cleaning Notebook](https://github.com/Himanshu76-DA/Customer-segmentation-team-project-/blob/main/Olis_Dataset_jup.ipynb)  

---

## 🔹 RFM Clustering  
**Performed by:** [me](https://github.com/Himanshu76-DA)  

### ⚙️ Key Tasks:
- Segmented customers using **RFM Analysis** to measure engagement  
- Clustered customers into actionable groups using **K-Means Clustering**  
- Visualized results in **2D and 3D plots**  
- Created RFM and RFM_stats summary tables and exported results for further use  

**📂 Files:**  
- [RFM Table](https://github.com/Himanshu76-DA/Customer-segmentation-team-project-/blob/main/RFM_Olis_cust_data.csv)  
- [RFM Summary Stats](https://github.com/Himanshu76-DA/Customer-segmentation-team-project-/blob/main/RFM_stats_data.csv)  
- [Notebook](https://github.com/Himanshu76-DA/Customer-segmentation-team-project-/blob/main/Olis_Dataset_jup.ipynb)  

**📊 Visuals:**  
![Customer Clustering 2D](https://raw.githubusercontent.com/Himanshu76-DA/Customer-segmentation-team-project-/main/Customer%20clustering.png)  
![Customer Clustering 3D](https://raw.githubusercontent.com/Himanshu76-DA/Customer-segmentation-team-project-/main/Customer%20clustering%203d%20graph.png)  

### 💡 Key Insights:
1. **High-Value Customers (665)** → Contribute ~15% of total revenue, avg monetary = ₹670  
2. **Inactive Customers (400)** → Total monetary = ₹10L, avg = ₹26  
3. **Loyal Customers (352)** → Purchase **2.17× more frequently**, ideal for loyalty campaigns  
4. **Super Frequent Buyer (1 record)** → 21 purchases — likely an outlier/test account  

---

## 🔹 Exploratory Data Analysis (EDA)  
**Performed by:** [Nandini](https://github.com/nandiniarjun03)
  
**📂 Files:** 

- **Dataset Used:** [Cleaned Dataset](https://github.com/Himanshu76-DA/Customer-segmentation-team-project-/blob/main/Olis_Order_Dataset(EDA).zip.zip)  
- **Notebook:** [EDA File](https://github.com/Himanshu76-DA/Customer-segmentation-team-project-/blob/main/Olis_data_jup(Eda)%20Final%20File.ipynb)  

### 📊 Visual Insights  

#### 1. Delivery Speed vs Ratings  
![Heatmap](https://raw.githubusercontent.com/Himanshu76-DA/Customer-segmentation-team-project-/main/Heatmap.png)  
> ⚡ Customers receiving faster deliveries tend to leave higher ratings.  

#### 2. Profit Over Time  
![Profit Over Time](https://raw.githubusercontent.com/Himanshu76-DA/Customer-segmentation-team-project-/main/Profit%20over%20time.png)  
> 📈 December 2017 marked the highest profit peak.  

#### 3. Average Delivery Time per State  
![Avg Delivery Time per State](https://raw.githubusercontent.com/Himanshu76-DA/Customer-segmentation-team-project-/main/Avg%20delivery%20time%20per%20states.png)  
> ⏱️ *RR* state recorded the highest average delivery time.  

#### 4. Average Delivery Time per Product Category  
![Avg Delivery Time per Product Category](https://raw.githubusercontent.com/Himanshu76-DA/Customer-segmentation-team-project-/main/Avg%20delivary%20days%20per%20product%20category.png)  
> 📦 *Movies Escritorio* category faced the longest delivery delays.  

#### 5. Delayed Deliveries by State  
![Delayed Cases by State](https://raw.githubusercontent.com/Himanshu76-DA/Customer-segmentation-team-project-/main/Customer%20Counts%20by%20states%20having%20delayed%20delivery%20status.png)  
> ⚠️ *SP* state reported the highest delay count (1,750 cases).  

#### 6. Loss Over Time  
![Loss Over Time](https://raw.githubusercontent.com/Himanshu76-DA/Customer-segmentation-team-project-/main/loss%20over%20time.png)  
> 💰 Losses were highest during months with low order volume and high cancellations.  

---

## 🔹 Power BI Dashboard  
**Created by:** [Himanshu](https://github.com/Himanshu76-DA)

This **interactive Power BI dashboard** visualizes customer segmentation insights, order performance, and key KPIs from the RFM and EDA analysis — providing a quick overview of the business’s customer behavior and sales trends.

**📂 Files:**  
- [Power BI File (.pbix)](https://github.com/Himanshu76-DA/Customer-segmentation-team-project-/blob/main/Olis%20Order%20Dashboard.pbix)  
- [Dashboard PDF Overview](https://github.com/Himanshu76-DA/Customer-segmentation-team-project-/blob/main/Olis%20Order%20Dashboard.pdf)

---

## Summary  
- Cleaned dataset and RFM clustering effectively identified **high-value and loyal customer segments**.  
- Visual insights highlighted patterns in **customer behavior, delivery performance, and sales trends**, aiding **targeted marketing and operational improvements**.  
- Analysis can be extended to **predictive modeling, churn analysis, or customer lifetime value estimation** for deeper business impact.  

---

## 🧾 Tools & Libraries  
- **Python:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook  
- **Power BI:** Interactive dashboards, KPI visuals, data modeling  
- **Techniques:** EDA, Data Cleaning, RFM Clustering, Customer Segmentation, Visualization  

---

## ⭐ Acknowledgment  
Special thanks to **RD Group of Industries** for their guidance and continuous support throughout the project.
