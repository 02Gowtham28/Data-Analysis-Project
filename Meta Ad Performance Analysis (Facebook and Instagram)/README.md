# 📊 Meta Ad Performance Analysis – Power BI Dashboard

This repository contains a complete **Power BI Business Intelligence project** designed to analyze advertising performance across Meta platforms (Facebook & Instagram).  
The dashboard provides insights into **campaign reach, engagement, conversions, time trends, budget efficiency, and audience behavior**.

---

# 📁 Project Files

- **Meta.pbix** → Power BI dashboard  
- **META Ad Performance Analysis.pdf** → Project explanation & documentation  
- **/assets** → Folder where you will add dashboard screenshots (explained below)  
- **README.md** → This file  

---

# 📌 Project Overview

This project evaluates the effectiveness of Meta advertising campaigns using the following key KPIs:

- Impressions  
- Clicks  
- Engagements  
- Purchases (Conversions)  
- CPM, CPC, CTR, ROAS  
- Demographics (Age, Gender, Country, City)  
- Time-based behavior (Hourly, Daily, Weekly)

The dashboard helps marketing teams identify **funnel drop-offs**, optimize **targeting**, and improve **ROI**.

---

# 🛠️ Data Architecture

The data model follows a clean **Star Schema** for optimal performance.

### **Fact Table**
- **ad_events**  
  Contains all interaction events (Impression, Click, Like, Share, Purchase)

### **Dimension Tables**
- **ads** – creative details  
- **campaigns** – campaign-level attributes  
- **users** – demographic information  
- **Calendar** – DAX-generated date table for time intelligence  

---

# 🔄 Data Preparation (Power Query)

Key transformations:

1. Loaded four CSV files using Import Mode  
2. Data type corrections for keys  
3. Converted timestamps into proper DateTime  
4. Created a full Date table using DAX  
5. Standardization of foreign key relationships  

---

# 📊 Dashboard Pages  

Below are the dashboard pages.  
<img width="1742" height="1061" alt="Screenshot 2025-11-17 115214" src="https://github.com/user-attachments/assets/7503a029-5e21-4ee1-aedb-89e10da1c63d" />

---

## **1️⃣ Overview Dashboard**

<img width="1187" height="182" alt="image" src="https://github.com/user-attachments/assets/73690839-d889-483d-8700-ed93e7c85334" />

This page summarizes overall campaign performance:  
- Impressions  
- Clicks  
- CTR  
- Engagements  
- Purchases  
- ROAS & Budget usage  

---

## **2️⃣ Audience Insights**

<img width="386" height="326" alt="image" src="https://github.com/user-attachments/assets/12a9c167-06e7-4f9e-b6c6-ad79258f57d0" />
<img width="566" height="334" alt="image" src="https://github.com/user-attachments/assets/fcb89f70-b461-44d1-9b76-22cf1a2abed9" />
<img width="499" height="485" alt="image" src="https://github.com/user-attachments/assets/b5dac2ac-4964-4a8e-8cd2-4641ff9f04d4" />

Insights include:  
- Gender distribution  
- Age groups  
- Countries & cities  
- User interests  

---

## **3️⃣ Funnel Performance**

<img width="557" height="274" alt="image" src="https://github.com/user-attachments/assets/0082e144-e443-44a3-8a4f-8dc231c5120c" />

Shows the flow:  
**Impressions → Clicks → Engagement → Purchase**

Used to identify where performance drops.

---

## **4️⃣ Time & Seasonality Analysis**

<img width="603" height="595" alt="image" src="https://github.com/user-attachments/assets/c33120c7-ab7b-43c9-8aa6-c205e8086ba3" />
<img width="491" height="519" alt="image" src="https://github.com/user-attachments/assets/1f0d7d60-227b-4f20-8555-961fc76f5519" />

Includes:  
- Hourly trends  
- Daily peaks  
- Weekly engagement patterns  
- Seasonal performance spikes  

---

# 📈 Key Insights From Analysis

- **CTR is very high (~11.76%)**, showing strong ad creatives  
- Engagement rate is also high (13.56%)  
- But **purchase conversion drops**, indicating funnel leakage  
- Most active audience: **Females, 18–30 age group**  
- Top engagement countries: **India, Brazil**  
- High-value customers: **UK, Germany**  
- Best performing ad formats: **Video & Stories**  
- Engagement peaks during **afternoons & evenings**

---

# 💡 Recommendations

1. Improve landing page experience  
2. Increase targeting towards high-quality audiences (UK, Germany)  
3. Allocate more budget to **Video & Stories**  
4. Schedule ads during peak active times  
5. Implement retargeting for cart abandoners  

---

# 🚀 How to Use This Project

1. Clone or download this repository  
2. Open **Meta.pbix** in Power BI Desktop  
3. Add your own dataset if needed  
4. Place dashboard screenshots inside `/assets` folder  
5. Replace screenshot placeholders in this README  

---

# 📌 Future Improvements

- Automating refresh using Meta Ads API  
- Adding ML-based ROAS prediction  
- Creating advanced segmentation dashboards  

---

# 👨‍💻 Author

**Gowtham R**  
*Junior Data Analyst*  
https://linkedin.com/in/28gowtham/

---

# ⭐ Support

If you like this project, feel free to **star ⭐ this repository**!

