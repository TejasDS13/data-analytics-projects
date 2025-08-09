# Spotify Global Hits 2024: An Interactive Dashboard

here are the views of dashboards
<img width="1457" height="816" alt="image" src="https://github.com/user-attachments/assets/f1dafd57-55f7-45b1-b035-4c7f2cc313f5" />
<img width="1448" height="813" alt="image" src="https://github.com/user-attachments/assets/d048a882-96ff-4cde-ac35-66088af8eb91" />
<img width="1446" height="805" alt="image" src="https://github.com/user-attachments/assets/cc66c49f-cf12-4abb-989e-d1fa8d65a106" />
<img width="1445" height="813" alt="image" src="https://github.com/user-attachments/assets/6a204b4d-9b01-4766-8684-9d3aa6b61de8" />

## 🚀 Project Overview

This project is a comprehensive analysis of the most streamed Spotify songs of 2024. The goal was to use Power BI to transform a raw dataset into an insightful, interactive dashboard that explores the anatomy of a modern hit song, from its streaming performance to its cross-platform success and release trends.


## 📊 Key Insights

- **Strong Cross-Platform Correlation:** A significant positive correlation was found between a song's Spotify streams and its YouTube views, indicating that success on one platform strongly predicts success on the other.
- **The Dominance of Recent Hits:** The vast majority of top-performing songs were released in 2024, highlighting the fast-paced nature of the music industry.
- **Top Artist Dominance:** A small number of artists, such as [mention 1-2 artists you found], are responsible for a large portion of the hit songs in the dataset.
- **Explicit Track Performance:** The analysis showed that [Explicit/Non-Explicit] tracks, on average, tend to generate more streams.

---

## 🛠️ Technical Skills & Tools Used

- **Data Cleaning & ETL:** Power Query (M Language)
  - Handled data type conversions, removed delimiters, and replaced null/error values.
  - Created conditional columns (e.g., for Track Type) and custom columns (e.g., for a numeric date representation) to enhance the dataset for analysis.
- **Data Modeling:**
  - Designed a Star Schema with a fact table and a dedicated Date Dimension (`DimDate`) table.
  - Established and managed relationships between tables.
- **Data Analysis:** DAX (Data Analysis Expressions)
  - `SUM`, `COUNT`, `CALENDAR`
- **Reporting & Visualization:** Power BI Desktop
  - Utilized a variety of visuals including Bar Charts, Line Charts, Scatter Plots, Donut Charts, and KPI Cards.
  - Implemented `Top N` filters for focused analysis.
  - Created a custom navigation page with Page Navigator buttons for an enhanced user experience.

---

## 📂 Data Source

The dataset used for this analysis is the "Most Streamed Spotify Songs 2024," sourced from Kaggle website
