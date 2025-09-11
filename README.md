# COVID-19 Exploratory Data Analysis (EDA) & Power BI Dashboard

📊 Repository: [COVID_19_EDA](https://github.com/Juligatuna/COVID_19_EDA.git)

This project explores global COVID-19 data through **data cleaning, analysis, and visualization**.  
The goal is to generate insights on cases, deaths, and vaccinations, and present them in an **interactive Power BI dashboard**.

---

## 📂 Project Structure


COVID_19_EDA/
│
├── data/
│ ├── covid_snapshot.csv # Latest snapshot per country
│ ├── covid_timeseries.csv # Full historical timeseries
│ └── cleaned_covid19_data.csv # Cleaned dataset (latest per country)
│
├── notebooks/
│ └── covid_eda.ipynb # Jupyter notebook for data cleaning & EDA
│
├── dashboard/
│ └── covid_dashboard.pbix # Power BI dashboard file
│
└── README.md # Project documentation

---

## 🔎 Exploratory Data Analysis (EDA)

1. **Data Cleaning**  
   - Removed duplicates and unnecessary rows.  
   - Kept only latest cumulative totals per country.  

2. **EDA Highlights**  
   - Top countries by cases & deaths.  
   - Global mortality rate (CFR).  
   - Vaccination progress over time.  
   - Trend of daily cases and deaths.

---

## 📊 Power BI Dashboard Features

1. **Global Overview**  
   - Total cases, deaths, vaccinations (cards).  
   - Daily new cases trend (line chart).  

2. **Top Countries Analysis**  
   - Bar chart: top 10 countries by cases/deaths.  
   - Map visualization: cases & deaths per million population.  

3. **Vaccination Progress**  
   - Line chart: vaccination trend over time.  
   - % fully vaccinated population per country.  

4. **Comparisons**  
   - Country slicer: compare a country vs. global average.  
   - KPIs: mortality rate (CFR), vaccination coverage, cases per million.  

5. **Interactive Table**  
   - Searchable summary table of all countries.

---

## 📈 Key Metrics

- **Case Fatality Rate (CFR):** `Total Deaths ÷ Total Cases`.  
- **Vaccination Coverage:** `% of population fully vaccinated`.  
- **Cases Per Million:** Normalized case counts for fair comparison.  

---

## 🚀 How to Use

1. Clone the repo:  
   ```bash
   git clone https://github.com/Juligatuna/COVID_19_EDA.git
2. Open the Jupyter notebook for EDA.

3. Open the Power BI dashboard (.pbix) to interact with the visuals.

📌 Next Steps

-Automate data refresh using APIs.

-Add advanced analytics (forecasting, clustering).

-Deploy Power BI report online for live interaction.

👤 Author: Julius Irungu
📧 Contact: www.linkedin.com/in/julius-irungu-344519a8