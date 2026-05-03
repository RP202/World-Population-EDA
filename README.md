# 🌍 World Population Data Analysis (EDA)

## 📌 Overview
This project performs an **Exploratory Data Analysis (EDA)** on a global population dataset spanning from 1970 to 2022. The goal is to uncover patterns, relationships, and trends across countries and continents, deriving data-driven insights through correlation analysis and data visualization.

---

## 📂 Dataset Overview
The dataset contains information regarding population dynamics, covering:
*   **Timeframe:** 1970–2022 (Population of various years)
*   **Geographic:** Continent, Country, Area (km²)
*   **Metrics:** Density, Growth Rate, World Population Percentage, Rank

---

## 🛠️ Tech Stack
*   **Language:** Python
*   **Libraries:** Pandas, NumPy, Matplotlib, Seaborn

---

## 📊 Key Findings & Insights
*   **Population Stability:** Population counts across different years show a **very strong positive correlation (~1.0)**, indicating consistent, long-term trends.
*   **Area vs. Population:** There is a **moderate positive correlation (~0.45–0.53)** between area ($km^2$) and total population; larger countries generally have higher populations.
*   **Density Independence:** Population density shows a **very weak correlation (~0.1 or less)**, meaning higher density does not necessarily imply a higher total population.
*   **Growth Trends:** Growth rate has a **negligible correlation (~0)** with total population, indicating that population size does not influence growth speed.
*   **Ranking:** Rank is **negatively correlated** with population (lower rank number = higher population).
*   **Redundancy:** Multiple population columns across years are highly collinear.

---

## 🌍 Continent Insights
*   **Asia** holds the highest population concentration.
*   **Africa** follows as the next major contributor to global population.
*   **Oceania** has the lowest population levels.

---
---

## 📊 Key Findings & Insights
*   **Population Stability:** Population counts across different years show a **very strong positive correlation (~1.0)**, indicating consistent, long-term trends.
*   **Area vs. Population:** There is a **moderate positive correlation (~0.45–0.53)** between area ($km^2$) and total population; larger countries generally have higher populations.
*   **Density Independence:** Population density shows a **very weak correlation (~0.1 or less)**, meaning higher density does not necessarily imply a higher total population.
*   **Growth Trends:** Growth rate has a **negligible correlation (~0)** with total population, indicating that population size does not influence growth speed.
*   **Ranking:** Rank is **negatively correlated** with population (lower rank number = higher population).
*   **Redundancy:** Multiple population columns across years are highly collinear.

---

## 🌍 Continent Insights
*   **Asia** holds the highest population concentration.
*   **Africa** follows as the next major contributor to global population.
*   **Oceania** has the lowest population levels.

---

## 📈 Visualizations
*   **Correlation Heatmap:** Used to identify strong vs. weak relationships between variables.

---
## 🚀 Project Outcomes
*   Performed structured EDA to analyze global trends.
*   Interpreted correlation matrices to identify redundant features and key drivers.
*   Visualized data to present clear, actionable insights.

---

## 📂 Project Structure
```text
📁 World-Population-EDA
│── README.md
│── world_population.csv
│── eda_notebook.ipynb
```

---

## 👩‍💻 Author
**Rupali Pasa**
