
# Road Accident Analytics Dashboard – Tableau Project

## 📊 Project Overview

This project is a comprehensive Tableau-based dashboard that analyzes road accident data consisting of **nearly one million records**. The goal is to mimic a real-time analytics setup to uncover patterns, highlight peak accident hours, and identify root causes to help policymakers and safety authorities make informed decisions. 

> ⚠**Note:** The dataset used is not real-time or pulled from a live API. It is a static dataset designed to simulate real-world conditions for learning and demonstration purposes.

---

## Files Included

- `accident data.csv`: Raw dataset containing accident records.
- `Accidentanalyticsaman.twbx`: Tableau workbook file with complete dashboards and visualizations.
- `[Video link](https://youtu.be/5xW0N_siX8k)`: Video demonstration of dashboard functionality. 

---

## Tools & Technologies Used

- **Tableau Desktop** – for building interactive dashboards.
- **Microsoft Excel** – for initial data cleaning and preparation.
- **PowerPoint** – used to design a custom dashboard background.
- **Calculated Fields & Parameters**
- **Filters, Groups & Aggregates**

---

## 🛠Data Preparation & Cleaning

- Performed **data cleaning in Excel**:
  - Removed irrelevant columns and empty/null rows.
  - Standardized date formats for accurate time-based visuals.
  - Re-grouped accident causes and categories for concise insights.
- Handled over **1 million rows** of data, ensuring Tableau performance and visual clarity.
- Created new derived columns such as:
  - `Time of Day` buckets (Morning, Afternoon, Evening, Night)
  - `Day of Week` for weekly trend analysis
  - `Accident Severity` classifications
- Grouped similar rows and values using Tableau’s built-in grouping feature to improve clarity and eliminate duplication.

---

## Dashboard Design

- Designed a **custom background in PowerPoint** for use in the Tableau dashboard to enhance aesthetics and layout consistency.

---

## Dashboard Features & Visuals

### 1. **Summary Metrics Panel**
- High-level KPIs such as:
  - Total Accidents
  - % Severe vs Minor Accidents
  - Average Accidents per Day
- Interactive tooltips and filters for quick insight.

### 2. **Accident Frequency Heatmap**
- Visualizes accident frequency by **Day of Week** and **Hour of Day**
- Helps identify peak hours and days (e.g., Friday evenings)

### 3. **Top Causes of Accidents**
- Horizontal bar chart showing the **most frequent accident causes**
- Grouped causes such as "Distracted Driving," "Speeding," and "Weather Conditions" make the visual concise and readable.

### 4. **Severity Breakdown Pie/Donut Chart**
- Displays the ratio of minor vs severe accidents.
- Useful for understanding how serious the majority of cases are.

### 5. **Time of Day Trend Line**
- Line chart showing accident trends throughout the day.
- Can be filtered by severity, day, or cause.

### 6. **Interactive Filters & Parameters**
- Users can filter the data by:
  - **Accident Type**
  - **Time of Day**
  - **Day of Week**
  - **Cause of Accident**
  - **Severity**
  - **Year** – to compare year-over-year patterns and trends
- Parameters allow toggling between visual views or focus categories.

---

## Key Insights

- Most accidents happen during **evening hours** and **weekends**.
- **Speeding and distracted driving** are top contributors.
- Severe accidents are less frequent but cause significant delays and impacts.
- Grouping similar causes improved the storytelling aspect of the dashboard.

---

## How to Use

1. Make sure both files are in the same directory.
2. Open the `.twb` file (`Accidentanalyticsaman.twbx`) in Tableau Desktop.
3. If prompted, reconnect the data source to `accident data.csv`.
4. Interact with the filters and dashboards to explore accident insights.

---

## Video Demonstration

A video walkthrough of the dashboard functionality is included to showcase its interactive capabilities and insights.  
▶️ *File name:* `AATWB.mp4`

---

