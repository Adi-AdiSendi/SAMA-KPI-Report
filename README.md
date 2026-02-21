# SAMA-KPI-Report
# Saudi Arabia Economic Dashboard — Vision 2030 Progress Tracker

An interactive Power BI dashboard analyzing Saudi Arabia's economic transformation using official data from the Saudi Central Bank (SAMA) Open Data Portal. This study examines 20 years of economic indicators (2005–2024) across seven categories to track the Kingdom's diversification progress under Vision 2030, Read the SAMA_Analysis_Report for more information.

## 🔗 Live Dashboard

**[View the Dashboard on Power BI](https://app.powerbi.com/view?r=eyJrIjoiZmY4YmMyODktNDg3NS00Njk3LWJlZjQtYzUwOTUzZDdmYTFkIiwidCI6IjQzNjcxOTEyLTk4YWUtNDBhMC1hYmE1LTNjYmZiZGI2YjA3MiIsImMiOjl9)**

## 📊 Dashboard Structure

The dashboard consists of **8 pages**, each focused on a specific economic category:

| Page | Description | Key Visuals |
|------|-------------|-------------|
| **Home** | Main navigation hub with 7 category cards | Category icons linking to each section |
| **National Accounts** | GDP breakdown, sector composition, diversification | Dual line chart, Donut, Non-Oil GDP % line |
| **Public Finance** | Revenue, expenditure, fiscal balance, debt | Stacked bar, Grouped bar, Deficit bar, Non-Oil Revenue % |
| **External Sector** | Exports, imports, trade balance | Export composition bar, Trade balance, Import treemap |
| **Energy Sector** | Oil production, exports by destination | Stacked bar by region, Production line |
| **Price Indices** | CPI breakdown by category | Stacked bar by type, General Index line |
| **Monetary & Financial** | Money supply M1/M2/M3, SME credit | Multi-line chart (M1/M2/M3) |
| **Other Statistics** | Population by gender, growth trends | Grouped bar (male/female), Population growth line |

## 📁 Data Sources

All data sourced from the **Saudi Central Bank (SAMA) Open Data Portal**: [https://www.sama.gov.sa](https://www.sama.gov.sa)

| File | Columns | Coverage | Key Metrics |
|------|---------|----------|-------------|
| `National_Accounts.xlsx` | 71 | 2005–2024 | GDP, sector breakdown, oil vs non-oil, services share |
| `Public_Finance.xlsx` | 43 | 2005–2024 | Revenue (oil/non-oil), expenditure by sector, debt, deficit |
| `External_Sector.xlsx` | 45 | 2005–2024 | Exports by type, imports by 21 commodity groups, trade balance |
| `Energy_Sector.xlsx` | 15 | 2005–2022 | Oil production, spot prices, exports by destination |
| `Price_Indices.xlsx` | 15 | 2013–2024 | CPI by 14 categories |
| `Monetary_and_Financial_Statistics.xlsx` | 15 | 2005–2024 | Money supply M1/M2/M3, SME credit facilities |
| `Other_Miscellaneous_Statistics.xlsx` | 28 | 2005–2024 | Population, unemployment, labor force |

## 🛠 Data Preparation

- Data downloaded directly from SAMA Open Data Portal as Excel files
- Cleaned and transformed in Power Query
- No external joins or third-party data — 100% SAMA sourced
- Years with incomplete data excluded from affected visuals

## 🔧 Tools Used

- **Power BI Desktop** — Dashboard creation and publishing
- **Power Query** — Data cleaning and transformation
- **DAX** — Calculated measures and KPIs
- **SAMA Open Data Portal** — Primary data source

## 📄 License & Disclaimer

This project is licensed under the [MIT License](LICENSE). See [DISCLAIMER.md](DISCLAIMER.md) for copyright and data attribution details regarding SAMA content.

## 👤 Author

**Adi Sendi**  
February 2026
