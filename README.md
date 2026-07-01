# 🏨 Atlas Hospitality Insights Dashboard

## 📌 Project Overview

This project showcases an end-to-end **Power BI Dashboard** developed for **Atlas Hospitality** to analyze hotel performance and generate actionable business insights. The dashboard helps stakeholders monitor revenue, occupancy, booking trends, customer ratings, and property-level performance across multiple cities.

The solution focuses on transforming raw hospitality data into interactive visualizations that support data-driven decision-making.

---

## 🎯 Business Problem

Atlas Hospitality operates multiple properties across major cities and needed a centralized reporting solution to:

- Track Revenue and Occupancy performance
- Monitor hotel KPIs across properties
- Analyze booking behavior and platform contribution
- Compare Luxury and Business hotel segments
- Identify trends and opportunities for growth

---

## 📊 Dashboard Highlights

### Executive Dashboard

- Revenue Analysis by City
- Occupancy Analysis by City
- Average Rating by City
- Booking Distribution by Platform
- Revenue Split (Weekdays vs Weekends)
- Occupancy & Rating Trend Analysis
- Dynamic Filters and Slicers

### Performance Dashboard

- Revenue KPI
- RevPAR KPI
- ADR KPI
- Occupancy %
- DSRN
- Realization %
- Week-on-Week Trend Analysis
- Occupancy by Category
- ADR & Realization by Platform
- Property-Level Performance Analysis

---

## 📈 Key Metrics Used

### ADR (Average Daily Rate)

```DAX
ADR =
DIVIDE(
    SUM(Room_Revenue),
    SUM(Rooms_Sold)
)
```

### RevPAR (Revenue Per Available Room)

```DAX
RevPAR =
DIVIDE(
    SUM(Room_Revenue),
    SUM(Available_Rooms)
)
```

### DSRN (Daily Sellable Room Nights)

```DAX
DSRN =
DIVIDE(
    SUM(Room_Revenue),
    SUM(Nights)
)
```

---

## 🛠️ Tools & Technologies

- Power BI
- DAX
- Data Modeling
- Power Query
- Data Visualization
- Business Intelligence

---

## 📌 Key Insights

- Mumbai generated the highest revenue among all cities.
- Overall occupancy remained around **58%**.
- Luxury and Business segments showed similar occupancy performance.
- Online travel platforms contributed significantly to bookings.
- Weekday revenue outperformed weekend revenue.
- Property-level analysis helped identify top-performing hotels.

## 🚀 Skills Demonstrated

- Data Cleaning
- Data Modeling
- DAX Calculations
- Dashboard Design
- Business Intelligence
- Data Storytelling
- KPI Development
- Hospitality Analytics
