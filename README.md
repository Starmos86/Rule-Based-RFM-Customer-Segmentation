# Customer Segmentation Analysis Using RFM Framework

## 📊 Project Overview

This project applies **RFM (Recency, Frequency, Monetary) analysis** to segment retail customers based on purchasing behavior and generate actionable business insights for **customer retention, engagement, and revenue optimization**.

Customers are evaluated across three behavioral dimensions:

- **Recency** → How recently a customer made a purchase  
- **Frequency** → How often a customer makes purchases  
- **Monetary** → How much revenue a customer generates  

The project combines analytical and business-driven approaches, including:

- Exploratory Data Analysis (EDA)  
- Quantile-based RFM scoring  
- Rule-based customer segmentation  
- Revenue concentration analysis  
- Business insights generation  

---

## 🔑 Key Insights

- ~49.9% of customers generate ~80% of total revenue (Pareto effect)
- Champions and Loyal Customers are the primary revenue drivers
- Purchase Frequency is the strongest indicator of customer value
- Several segments show clear churn-risk behavior
- Customer value is multi-dimensional and cannot be explained by a single metric alone

---

## 📦 Dataset Information

- **Dataset:** Superstore retail dataset  
- **Records:** 10,000+ transactions  
- **Regions:** United States and Canada (analysis focused on U.S.)  
- **Time period:** January 2021 – December 2024  

---

## ⚙️ Methodology

The analysis follows this workflow:

1. Data Cleaning & Preparation  
2. RFM Metric Computation  
3. Quantile-Based RFM Scoring  
4. Rule-Based Customer Segmentation  
5. Exploratory Data Analysis (EDA)  
6. Revenue & Behavioral Analysis  
7. Business Recommendations  

---

## 👥 Customer Segments

The project identifies the following customer groups:

- Champions  
- Loyal Customers  
- Potential Loyalists  
- New Customers  
- Need Attention  
- At Risk  
- Hibernating  
- Lost  

---

## 📈 Visualizations

The project includes the following key visualizations:

- Customer Distribution Across RFM Segments
<img width="4752" height="2952" alt="customer_distribution_by_segment" src="https://github.com/user-attachments/assets/048e69b9-90d4-49de-938e-22abd16a4dbe" />

<br>
- Revenue Contribution by Segment
<img width="4752" height="2952" alt="Revenue_share_by_segment" src="https://github.com/user-attachments/assets/b3900ce5-c6f1-430c-913c-bc8c96860710" />

- Average RFM Scores by Segment
<img width="4752" height="2952" alt="heatmap" src="https://github.com/user-attachments/assets/538bb1d2-5a7a-48f7-9b98-3541bb515335" />


- Pareto (80/20) Revenue Analysis  
<img width="4752" height="2952" alt="Pareto" src="https://github.com/user-attachments/assets/3cb91331-e969-4590-b570-bdbd1aea5739" />

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## Conclusion

This project demonstrates how RFM analysis can transform raw transaction data into clear business insights for customer segmentation and decision-making.

## 📁 Repository Structure

```bash
├── data/                # Dataset files
├── notebooks/           # Jupyter notebooks
├── images/              # Visualizations
├── README.md
└── requirements.txt


