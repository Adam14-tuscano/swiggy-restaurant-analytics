# 🍽️ Swiggy Restaurant Performance & Delivery Analytics

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-FC8019?style=flat&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## 📌 Project Overview

A real-world business analytics case study analyzing **8,675 restaurants** 
across **9 Indian cities** on the Swiggy food delivery platform. 
Built to identify delivery performance gaps, rating issues, and 
cuisine-level insights using Python and Power BI.

---

## 🚨 Key Findings

| Metric | Value | Target | Status |
|--------|-------|--------|--------|
| Avg Delivery Time | 53.94 mins | ≤ 30 mins | 🔴 BREACH |
| SLA Breach Rate | 70.49% | < 20% | 🔴 CRITICAL |
| Poor Rated Restaurants | 40.56% | < 15% | 🔴 CRITICAL |
| Avg Customer Rating | 3.66 / 5.0 | ≥ 4.0 | 🟡 BELOW TARGET |
| Fast Delivery (≤30 min) | 2.5% only | > 50% | 🔴 CRITICAL |

---

## 📊 Dashboard Pages

### Page 1 — Executive KPIs
![Page 1](https://github.com/Adam14-tuscano/swiggy-restaurant-analytics/blob/main/Screenshot%202026-06-15%20011219.png)

### Page 2 — City & Cuisine Analysis
![Page 2](https://github.com/Adam14-tuscano/swiggy-restaurant-analytics/blob/main/Screenshot%202026-06-15%20011249.png)

### Page 3 — Delivery Performance
![Page 3](https://github.com/Adam14-tuscano/swiggy-restaurant-analytics/blob/main/Screenshot%202026-06-15%20011304.png)

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python (Pandas, NumPy) | Data cleaning & EDA |
| Matplotlib, Seaborn | EDA visualizations |
| Power BI Desktop | Interactive dashboard |
| DAX (8 measures) | KPI calculations |
| Google Colab | Cloud Python environment |
| GitHub | Version control & portfolio |

---

## 📁 Project Structure

```
swiggy-restaurant-analytics/
├── data/              → Cleaned dataset (8,675 rows, 17 columns)
├── notebooks/         → Python EDA & cleaning notebook
├── charts/            → 6 EDA charts (PNG)
├── dashboard/         → 3 dashboard screenshots (PNG)
├── reports/           → BRD + Insights Report (DOCX)
└── README.md
```

---

## 💡 5 Key Insights

1. **Delivery Crisis** — 70.49% of restaurants breach the 45-min SLA. 
   Only 216 restaurants (2.5%) meet the 30-min promise
2. **Rating Emergency** — 40.56% of restaurants rated below 3.5. 
   Pune worst city at 44% poor-rated
3. **Cuisine Quality Gap** — North Indian has most restaurants (2,438) 
   but ranks 6th in rating. Healthy Food scores highest at 4.02
4. **Delivery Drives Rating** — Cities with higher delivery time 
   consistently show lower ratings (Kolkata: 67.6 min, lowest rated)
5. **Price-Rating Mismatch** — Luxury restaurants (>₹700) do not 
   consistently outperform Mid-Range in customer satisfaction

---

## 📄 Documents

- 📋 [Business Requirements Document](https://github.com/Adam14-tuscano/swiggy-restaurant-analytics/blob/main/Swiggy_BRD.docx)
- 📊 [5-Point Insights Report](https://github.com/Adam14-tuscano/swiggy-restaurant-analytics/blob/main/Swiggy_Insights_Report.docx)

---

## 👤 Author

**Adam Tuscano**  
Aspiring Data Analyst | Power BI | Python | SQL  
[LinkedIn]https://www.linkedin.com/in/adam-tuscano-2727281b8/ | 
[Email](adamtuscano12@gmail.com)
