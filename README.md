# Gun Violence in the United States (2014–2022)
Interactive Tableau Dashboard | Data Visualization & Policy Analysis

---

## 📌 Project Overview

This project analyzes patterns of gun violence incidents in the United States from 2014 to 2022 using interactive data visualization in Tableau.

The objective is to identify geographic and temporal trends to support informed public policy discussion and data-driven decision-making.

---

## 🎯 Key Questions

1. Which states recorded the highest per-capita gun violence incident rates?
2. How did incidents, injuries, and fatalities change over time?
3. What patterns emerge when comparing injuries to fatalities?
4. Are there noticeable spikes or trend shifts across the study period?

---

## 📊 Data Sources

- Gun violence incidents dataset (Kaggle)
- U.S. Census state population totals

The datasets were joined in Tableau using a left join on **State**.

---

## 🧮 Methodology

To normalize incident counts across states with different population sizes, a per-capita incident rate was calculated:
(COUNTD([Incident ID]) / SUM([Population 2022])) * 100000


This allowed for fair comparison across states.

Visualizations included:
- Geographic distribution (choropleth map)
- State-level per-capita ranking (bar chart)
- Annual trend analysis (line chart)
- Injuries vs. fatalities comparison (stacked bar chart)
- Summary statistics table

---

## 📈 Key Findings

- Significant geographic clustering of gun violence incidents.
- Incident counts increased across the study period, with a notable peak around 2021.
- Injuries consistently exceed fatalities, indicating long-term public health impact beyond deaths.
- Per-capita normalization reveals disparities not obvious from raw counts alone.

---

## ⚖️ Ethical & Analytical Considerations

- Population normalization used 2022 Census data across all years.
- Reporting accuracy may vary by jurisdiction.
- This dashboard is intended for analytical and educational purposes.
- Sensitive topics require careful interpretation and responsible communication.

---

## 🛠 Tools Used

- Tableau Desktop
- Data cleaning and aggregation
- Geographic mapping
- Time series analysis

---

## 📂 Repository Structure

- `/tableau` – Packaged Tableau workbook (.twbx)
- `/docs` – Final report
- `/images` – Dashboard screenshots

---

## 📚 Selected References

- CDC WISQARS
- Pew Research Center (U.S. Gun Death Trends)
- Goldstick et al., NEJM
- Kaufman et al., JAMA Internal Medicine
- Knaflic, *Storytelling with Data*

---

## 🔍 Why This Matters

Effective public policy requires evidence-based analysis.  
This project demonstrates how responsible data visualization can inform discussions around public safety, public health, and legislative decision-making.

## 🔐 Data Governance Relevance

This project highlights the importance of:
- Transparent data sourcing
- Proper normalization techniques
- Responsible communication of sensitive statistics
- Avoiding misleading visual representations

Strong data governance practices are essential when working with high-impact societal data.



