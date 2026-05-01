# 🌍 World Population EDA

## 📌 Overview

This project explores a global population dataset to uncover **patterns, relationships, and trends** across countries and continents using Exploratory Data Analysis (EDA).
The focus is on deriving **data-driven insights** through correlation analysis and visualizations.

---

## 📂 Dataset
* Global population data (1970–2022)
* Key features:
  * Population (multiple years)
  * Area (km²)
  * Density
  * Growth Rate
  * Continent
  * World Population %
  * Rank

---

## 🛠️ Tools Used
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 📊 Key Insights

* Population across years shows **very strong correlation (~1.0)**
  → Indicates consistent population distribution over time
  
* Area has a **moderate positive correlation (~0.45–0.53)** with population
  → Larger countries tend to have higher populations
  
* Population density shows **very weak correlation (~0.1 or less)**
  → Density is independent of total population
  
* Growth rate has **negligible correlation (~0)**
  → Population size does not influence growth trends

* Rank is **negatively correlated** with population
  → Higher population = lower rank number

* Multiple population columns are **highly correlated (redundant)**
  → Carry similar information

---

## 🌍 Continent Analysis

* Asia has the **highest population concentration**
* Africa follows as the next major contributor
* Oceania has the **lowest population levels**

---

## 📈 Visualization

### Correlation Heatmap

Used to quickly identify **strong and weak relationships** between variables.

---

## 🚀 Outcome

This project demonstrates the ability to:

* Perform structured EDA
* Interpret correlation effectively
* Extract meaningful insights from real-world data
* Present findings clearly

---

## 👩‍💻 Author

**Rupali Pasa**

---

## 📎 Project Structure

```
📁 World-Population-EDA
│── README.md
│── world_population.csv
│── eda_notebook.ipynb
```
## 👩‍💻 Author
Rupali Pasa
