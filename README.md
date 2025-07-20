# Payment Analytics and Anomaly Detection Pipeline

This project analyzes **synthetic insurance data (10,000+ rows)** to uncover hidden trends in **claim payouts**, **premium pricing**, **conversion rates**, and **risk anomalies**. The goal is to provide actionable insights to improve **policy pricing strategy**, **customer segmentation**, and **fraud/anomaly detection** using visual analytics.

---

## Dataset

The dataset is synthetic and created for educational/portfolio use, containing fields like:

- `Age`, `Credit Score`, `Premium Amount`, `Risk Score`, `Conversion Time`, `Anomaly Flag`, `Region`, etc.

---

##  Tools & Technologies

- **Tableau Public** (dashboard creation, interactive filters)
- **Python (Pandas, NumPy, Matplotlib)** – for pre-processing and risk scoring
- **Excel** – data formatting and validation

---

## Key Analyses Performed

- **Total Claims, Premium & Conversion Trends:**  
  Visualized YoY performance metrics across key KPIs with sparklines and % variance indicators.

- **Customer Age Distribution:**  
  Found the highest policyholder concentration between **30–49 years**, indicating the most insurable and active demographic.

- **Risk-Adjusted Premium Binning:**  
  Plotted premiums alongside an **anomaly threshold marker** (~1000) to spot high-risk underpriced customers.  
  About **9.8% of users** were flagged as high-risk with significantly higher claim ratios.

- **High-Risk Segmentation:**  
  Built a donut chart to show **proportion of high vs. low-risk customers**. This helps in fraud monitoring and pricing policy revisions.

- **Regional Premium Analysis:**  
  Compared total and discounted premiums across **Rural, Suburban, and Urban** regions.  
  Urban regions paid the highest premiums (~11M), but also received maximum discounts.

- **Conversion Funnel Analysis:**  
  Funnel stages from **Website Visits → Inquiries → Quotes → Conversions** were visualized.  
  Conversion drop-off was steep — only **5,767 conversions out of 50,229 visits** (~11.4%).

---

## Impact

- Identified **anomaly-prone segments** and underpriced policies using risk-adjusted metrics  
- Helped simulate pricing strategies by region and customer age  
- Surfaced actionable conversion funnel inefficiencies  
- Created a fully dynamic dashboard with filters for year and region type

---

## Dashboard Preview
[View Tableau Dashboard](https://public.tableau.com/app/profile/lekhana.s1303/viz/PaymentAnalyticsandAnomalyDetectionPipeline/Dashboard1)
![Dashboard](images/cPayments_Dashboard.png)
---

## 🔮 Future Improvements

- Integrate **real-time claims feed** for anomaly alerting  
- Add **policy type breakdowns** to segment pricing performance  

---


