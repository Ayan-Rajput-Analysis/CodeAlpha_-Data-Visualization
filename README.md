# 📊 Netflix Global Business Intelligence & Power BI Executive Dashboard

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-Executive%20BI-f2c811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/DAX-Advanced%20Measures-00599c?style=for-the-badge" alt="DAX">
  <img src="https://img.shields.io/badge/Data%20Modeling-Star%20Schema-green?style=for-the-badge" alt="Data Modeling">
  <img src="https://img.shields.io/badge/Executive-Presentation-orange?style=for-the-badge" alt="Presentation">
</p>

---

## 📌 Executive Dashboard Overview

A high-impact executive Business Intelligence dashboard designed and developed in **Microsoft Power BI** for global streaming analytics. This interactive reporting suite allows C-suite executives and content licensing directors to cross-filter international catalogs by release cadence, duration metrics, maturity ratings, and country distribution.

<p align="center">
  <img src="Netflix_Dashboard_Pic.png" alt="Netflix Power BI Executive Dashboard" width="800"/>
  <br/>
  <em>Figure 1: High-fidelity executive Power BI dashboard with interactive slicers, KPI tiles, and multi-axis charts.</em>
</p>

---

## 🏗️ Core Architecture & Data Modeling

* **Star Schema Architecture**: Clean relational dimensional model separating the central Titles Fact table from Date, Country, Category, and Rating dimensions.
* **Complex DAX Calculations**:
  - Movie % Share = DIVIDE(CALCULATE(COUNTROWS(Titles), Titles[Type] = "Movie"), COUNTROWS(Titles), 0)
  - YoY Title Growth % = DIVIDE([Total Titles] - [Prior Year Titles], [Prior Year Titles])
  - Average Duration (Min) = CALCULATE(AVERAGE(Titles[Duration_Minutes]), Titles[Type] = "Movie")
* **Custom Theme & Typography**: High-contrast, accessibility-focused visual design utilizing Netflix dark-mode aesthetics for enhanced readability and executive presentation.

---

## 🗂️ Included Deliverables

* **Data_VIsualization.pbix**: Complete, interactive Power BI Desktop report with all DAX measures, relationships, and bookmarks.
* **Netflix_Dashboard_New.mp4**: 60-second video walkthrough demonstrating cross-filtering, drill-through interactions, and dynamic slicers.
* **Presentation.pptx**: Comprehensive executive slide deck breaking down insights for stakeholder review.
* **Netflix_Dashboard_Pic.png**: High-resolution screenshot of the primary dashboard view.

---

## 👨‍💻 Author
**Ayan Rajput**  
- **GitHub:** [@Ayan-Rajput-Analysis](https://github.com/Ayan-Rajput-Analysis)  
- **LinkedIn:** [Ayan Rajput](https://www.linkedin.com/in/ayan-rajput-8781a7397/)