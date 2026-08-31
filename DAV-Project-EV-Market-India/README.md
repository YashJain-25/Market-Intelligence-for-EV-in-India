<div align="center">

# ⚡ Market Intelligence for Electric Vehicles in India

### A Data Analysis & Visualization (DAV) Project

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Viz-4C72B0)](https://seaborn.pydata.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

</div>

---

## 📌 Overview

India's electric vehicle (EV) industry is in a phase of rapid growth, fueled by government
incentives, falling battery costs, and rising demand for sustainable mobility. This project
turns a **raw, unclean dataset of 30,100 EV registration records across 32 attributes** into
**actionable market intelligence** through data cleaning, exploratory data analysis (EDA), and
visual storytelling.

The analysis answers **15 real-world market intelligence questions** covering registration
growth, manufacturer competitiveness, state-wise adoption, battery & pricing trends, charging
infrastructure, and subsidy effectiveness — concluding with data-driven strategic
recommendations for India's EV ecosystem.

| | |
|---|---|
| **Author** | Yash Jain |
| **Institution** | Techno NJR Institute of Technology |
| **Dataset Size** | 30,100 rows × 32 columns |
| **Deliverables** | Jupyter Notebook, Raw Dataset (CSV), Presentation (PPTX) |

---

## 🎯 Problem Statements

This project addresses the following market intelligence questions:

1. How has EV registration volume grown year-over-year across India?
2. Which manufacturers hold the largest share of the Indian EV market?
3. Which states have the highest EV adoption levels?
4. What is the distribution between two-wheeler (2W) and four-wheeler (4W) EV categories?
5. How is battery capacity (kWh) distributed across the EV fleet?
6. Is there a relationship between charging infrastructure availability and EV registrations?
7. How is manufacturer market share distributed within each EV category (2W vs. 4W)?
8. How do government subsidy amounts vary across different EV categories?
9. What are consumer preferences for EV classes (Passenger vs. Scooter)?
10. How is vehicle pricing distributed across the Indian EV market?
11. What is the relationship between driving range and vehicle price?
12. What are the month-on-month cumulative EV registration trends?
13. How does driving range vary across the top EV-adopting states?
14. Where are the biggest market opportunities based on urbanization and registration density?
15. What do year-on-year manufacturer growth patterns indicate about future EV trends?

---

## 🗂️ Repository Structure

```
DAV-Project-EV-Market-India/
├── notebooks/
│   └── Market_Intelligence_for_EV_in_India.ipynb   # Full analysis notebook
├── data/
│   └── Market_Intelligence_for_EV_in_India.csv     # Dataset (30,100 records)
├── presentation/
│   └── Market_Intelligence_for_EV_in_India.pptx    # Summary slide deck
├── images/                                          # (optional) exported chart images
├── requirements.txt                                 # Python dependencies
├── LICENSE
└── README.md
```

---

## 🧭 Methodology

The notebook follows a structured DAV workflow:

1. **Data Loading & Profiling** — shape, dtypes, null counts, unique-value inspection
2. **Data Cleaning**
   - Renaming columns for clarity
   - Duplicate detection & removal
   - Standardizing inconsistent categorical text (e.g., manufacturer name casing)
   - Missing-value treatment (median imputation for numeric fields, mode/placeholder for categorical)
   - Outlier treatment using the IQR method
3. **Exploratory Data Analysis (EDA)** — univariate, bivariate, and multivariate analysis using
   bar charts, line plots, box plots, scatter plots, swarm plots, a correlation heatmap, and a
   pair plot
4. **Insight Generation** — written observations after every visualization
5. **Conclusion & Strategic Recommendations** — synthesizing findings into actionable
   suggestions for OEMs, policymakers, and dealership networks

---

## 📊 Dataset Description

The dataset simulates India's EV registration landscape and includes:

- **Vehicle attributes:** Manufacturer, Model, Vehicle Category/Class, Fuel Type, Battery (kWh),
  Range (km), Charging Type, Price (INR)
- **Registration details:** Registration ID, Date, Year, Month, Quarter, State, District, RTO,
  Latitude/Longitude
- **Market metrics:** Registration Count, Market Share, YoY/MoM Growth, Sales Target
- **Macro & infrastructure indicators:** Charging Stations, Fuel Price, State GDP, Population,
  Urbanization Rate, Temperature, Festival season

> **Source:** Simulated dataset modeled on realistic patterns observed in India's EV market,
> compiled for academic analysis.

---

## 🚀 Getting Started

### Prerequisites

- Python 3.9+
- Jupyter Notebook / JupyterLab

### Installation

```bash
# Clone the repository
git clone https://github.com/<your-username>/DAV-Project-EV-Market-India.git
cd DAV-Project-EV-Market-India

# (Recommended) create a virtual environment
python -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

### Run the Analysis

```bash
jupyter notebook notebooks/Market_Intelligence_for_EV_in_India.ipynb
```

---

## 🔑 Key Insights

- India's EV market shows **consistent year-over-year growth**, indicating an active expansion
  phase rather than a plateau.
- Adoption is **concentrated among a handful of manufacturers and states**, with the top states
  contributing the majority of national registrations.
- **Two-wheelers dominate** overall EV adoption, reflecting affordability-driven consumer
  behavior in the current market phase.
- **Charging infrastructure availability correlates positively** with registration volume.
- Battery capacity, driving range, and price are **strongly interrelated**, with four-wheelers
  occupying the higher-battery, higher-range, higher-price segment.
- Several **high-urbanization states remain under-penetrated**, marking them as prime
  opportunities for market expansion.

---

## 💡 Strategic Recommendations

- Expand charging infrastructure in under-penetrated, high-urbanization states.
- Increase subsidy awareness campaigns in states with favorable demographics but low adoption.
- Promote long-range EV models in geographically larger states to address range anxiety.
- Strengthen manufacturer and dealership networks in high-opportunity regions.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| **Python** | Core programming language |
| **Pandas / NumPy** | Data manipulation & numerical computation |
| **Matplotlib / Seaborn** | Data visualization |
| **Jupyter Notebook** | Interactive analysis environment |

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

<div align="center">

Made with ⚡ by **Yash Jain**

</div>
