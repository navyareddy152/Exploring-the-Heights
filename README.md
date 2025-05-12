# 🏔️ Exploring the Heights: Visualizing Trends in Himalayan Mountaineering Expeditions (2020–2024)

This project explores trends, risks, and patterns in Himalayan mountaineering expeditions using data from the **Himalayan Database**. Through data cleaning, exploratory analysis, and meaningful visualizations, we examine how seasonality, oxygen use, team structure, and route selection relate to expedition outcomes.

> 📅 Course: INFO 511 – Foundations in Data Science  
> 🧠 Authors: Praveen Kumar Pappala, Sai Navya Reddy Busireddy, Gowtham Theeda  
> 📊 Tools Used: Python, pandas, seaborn, matplotlib, plotly, folium

---

## 📌 Project Purpose

This project investigates the following research questions:

- What environmental or strategic factors are associated with summit success?
- Do certain months, seasons, or team structures affect death rates?
- How do characteristics like peak height, accessibility, and mountain range influence climbing trends?

We emphasize **descriptive analysis**, focusing on visual patterns.

---

## 📊 Dataset Information

- **Source**: [The Himalayan Database](https://www.himalayandatabase.com/) via [TidyTuesday](https://github.com/rfordatascience/tidytuesday)
- **Files Used**:
  - `exped_tidy.csv`: Expedition-level details (e.g., season, success, oxygen use)
  - `peaks_tidy.csv`: Peak characteristics (e.g., height, status, first ascent)

These datasets are open-access and anonymized for public use. No IRB approval was required.

---

## 🔍 Key Features and Visualizations

- **Summit Success vs Oxygen Use** (Grouped Bar Plot)
- **Success Rate by Season and Year** (Heatmap and Bar Plot)
- **Member vs Hired Personnel Deaths** (Line Chart)
- **Peak Height by Mountain Range** (Horizontal Bar)
- **Open vs Closed Peaks by Height** (Violin Plot)
- **Geospatial Map of Top Peaks** (Folium Map)
- **Common Termination Reasons** (Bar Chart)
- **Monthly Summit Trends Over Years** (Multi-line Plot)
- **Route Success by Range** (Faceted Bar Chart)

All visualizations are produced in Python using `pandas`, `seaborn`, `matplotlib`, and `folium`.

---
