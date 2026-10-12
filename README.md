# 🌤️ North Africa Interactive Climate Analytics Dashboard

An end-to-end meteorological and climate data analytics project built exclusively in **Microsoft Excel**. This project transforms raw historical weather observations across North Africa into an interactive, dynamic decision-support dashboard.

---

## 📌 Executive Summary & Project Motivation

Atmospheric conditions across North Africa are governed by complex synoptic features, ranging from Saharan dust transport and atmospheric pressure gradients to marine-inland thermal contrasts. Analyzing these parameters is crucial for weather forecasting, climate monitoring, and regional environmental impact assessments.

The main objective of this project is to clean, process, and visualize regional weather observation data, enabling researchers and data analysts to extract instant climate insights per country and weather phenomenon.

---

## 📊 Project Scope & Dataset Summary

* **Total Records Analyzed:** 5,784 regional weather logs across North Africa (Egypt, Libya, Tunisia, Algeria, Morocco, Mauritania).
* **Core Metrics Tracked:** Average Temperature (°C), Visibility (km), Wind Speed (km/h), Max Wind Gusts (km/h), Atmospheric Pressure (mb), and Relative Humidity (%).
* **Analytical Focus:** Thermal spatial gradients, wind-driven visibility suppression, and synoptic pressure distribution across North Africa.

---

## 🧹 Data Cleaning & Preparation Pipeline

Before constructing the analytical dashboard, a rigorous data transformation pipeline was executed within Excel:

1. **Regional Filtering:** Applied multi-column wildcard and criteria filtering to scope the raw dataset exclusively to North African stations.
2. **Handling Missing Values:** Cleaned incomplete records and removed empty/blank category labels to prevent chart distortion.
3. **Data Type Standardization:** Converted raw text metrics into proper numerical formats (Single-Decimal accuracy) for temperatures, pressure, and visibility.
4. **Calculated KPI Logic:** Developed dynamic formulas to generate summary aggregates for average temperatures, visibility ranges, and maximum wind gust thresholds.

---

## 📌 Dashboard Preview

![North Africa Climate Dashboard](North-Africa-Climate-Dashboard.png)

---

## 📊 Visualizations Breakdown & Synoptic Analysis

### 1. Average Temperature by Country (°C) — [Horizontal Bar Chart]
- **Structure:** Horizontal bar chart ranking North African nations by mean thermal conditions.
- **Synoptic Insight:** Highlights strong continental-desert heating in inland regions (e.g., inland Saharan zones averaging up to ~29.9°C, Libya 26.4°C) compared to coastal-moderated Mediterranean/Atlantic zones (Morocco 18.5°C, Tunisia 22.0°C).

### 2. Wind Speed (km/h) vs. Pressure (mb) by Country — [Dual-Axis Combo Chart]
* **Structure:** Combo chart tracking average wind speed bars alongside an atmospheric pressure trendline.
* **Synoptic Insight:** Demonstrates classic baroclinic dynamics; lower surface pressures (~1010 mb) strongly correlate with elevated wind speeds, identifying active Saharan low-pressure cyclone tracks.

### 3. Max Wind Gusts by Country (km/h) — [Horizontal Bar Chart]
* **Structure:** Peak gust velocity ranking across regional stations.
* **Synoptic Insight:** Identifies peak wind speeds exceeding 70–72 km/h in Tunisia, Algeria, and Morocco. These high-energy gust events serve as the primary physical driver for dust deflation and mobilization.

### 4. Average Humidity (%) & Visibility (km) — [Dual-Axis Combo Chart]
* **Structure:** Dual-axis chart comparing relative humidity against horizontal visibility distances.
* **Synoptic Insight:** Captures severe visibility degradation (<6 km) during high-dust/gust periods, showcasing the direct impact of airborne dust aerosols on atmospheric clarity across arid zones.

### 5. Weather Condition Distribution — [Donut Chart]
* **Structure:** Categorical breakdown of 5,784 synoptic weather observations.
* **Synoptic Insight:** Reflects the dominant regional climate regime—predominantly Clear/Sunny (56%) and Partly Cloudy (29%), with intermittent dust storms, haze, and localized precipitation events.

---

## 🔑 Key Regional Insights

1. **Thermal Spatial Gradient:** High average temperatures are strongly concentrated in interior desert zones, creating strong local pressure deficits.
2. **Dust Suppression & Visibility Drop:** High wind gust events (>70 km/h) show a direct correlation with sharp drops in horizontal visibility (<6 km).
3. **Synoptic Regime:** Predominance of dry/sunny conditions (~85% combined clear/partly cloudy), with dust and haze events tightly coupled with peak atmospheric gustiness.

---

## 🛠️ Excel Architecture & Technical Features

* **Dynamic KPI Cards:** Custom merged-cell indicators linked dynamically to Pivot aggregates (`72.0 km/h` Peak Gusts, `8.96 km` Avg Visibility, `24.2°C` Avg Temp).
* **Multi-Parameter Slicers:** Synchronized interactive slicers for instant filtering by **Country** and **Weather Condition Text**.
* **UI/UX Polish:** Custom corporate dark-blue palette, zero gridlines, clean single-decimal formatting, and filtered empty `(blank)` categories.

---
## 📁 Repository Structure

* **`North_Africa_Climate_Dashboard.xlsx`** - Main interactive Excel workbook
* **`dashboard_preview.png`** - High-resolution dashboard screenshot
* **`README.md`** - Project documentation

---

## 👤 Author & Contact

* **Name:** Ahmed
* **Role:** Meteorological Specialist & Data Analyst
* **Specialization:** Atmospheric Science, Synoptic Analysis & Climate Data Analytics
* **Tools Used:** Microsoft Excel (Data Cleaning, Pivot Tables, Advanced Charting, Dynamic Slicers, KPI Logic)
* **GitHub Profile:** [github.com/ahmedhussein-meteodata](https://github.com/ahmedhussein-meteodata)
* **Kaggle Profile:** [kaggle.com/ahmedhussein77731](https://www.kaggle.com/ahmedhussein77731)
* **LinkedIn Profile:** [linkedin.com/in/ahmed-hussein-meteodata](https://www.linkedin.com/in/ahmed-hussein-meteodata)
