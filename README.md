# 🇹🇩 Chad Development Intelligence Dashboard

[![Live Dashboard](https://img.shields.io/badge/Live%20Dashboard-GitHub%20Pages-blue)](https://derio001.github.io/chad-development-dashboard)
[![Data](https://img.shields.io/badge/Data-INSEED%20Chad%20Official-green)](https://www.inseed.td)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)
[![Indicators](https://img.shields.io/badge/Indicators-98-orange)]()
[![Years](https://img.shields.io/badge/Coverage-1993--2024-red)]()

> **The first open-source interactive dashboard built exclusively on official Chad 
> government statistical data — making 30 years of development indicators 
> accessible and actionable for NGOs, policymakers, and researchers.**

## 🌐 Live Demo

👉 **[View the Dashboard](https://derio001.github.io/chad-development-dashboard)**

No installation needed. Works in any browser on any device.

---

## 📊 What's Inside

The dashboard integrates **12 official datasets** from INSEED Chad and the Chad Data 
Portal into 4 interactive sections:

### 🫁 Health & Nutrition
- Under-5 mortality trend (1996–2014)
- Food insecurity prevalence — 39% of population undernourished
- Vaccination coverage (BCG, Measles, Polio)
- Maternal mortality rate — 1,140 per 100,000 births (2018)
- Stunting and wasting prevalence in children

### 📈 Economy & GDP
- GDP trend 2005–2022 (current prices, FCFA)
- GDP breakdown by sector (Primary / Secondary / Tertiary)
- Poverty rate trend — 42% below poverty line (2018)
- Gini coefficient — income inequality index

### 🌾 Food Security
- Food insecurity by region (22 regions monitored)
- National food insecurity trend 2016–2024
- Over 6 million Chadians face acute food insecurity (2024)

### 👥 Demography
- Life expectancy trend (1993–2019) — from 47 to 54 years
- Fertility rate — 6.1 children per woman (2019)
- Population growth rate — 3% annually

---

## 🗄️ Integrated Dataset

`chad_inseed_master_dataset.csv` — All 12 official datasets merged into one 
clean master file.

| Field | Description |
|-------|-------------|
| `indicator` | Name of the statistical indicator |
| `region` | Chad region or TCHAD (national) |
| `unit` | Unit of measurement |
| `year` | Year of observation |
| `value` | Numerical value |
| `source` | Original INSEED dataset source |

**Stats:**
- 2,349 records
- 98 unique indicators
- 23 regions
- Coverage: 1993–2024
- 12 official source datasets

---

## 📁 Project Structure
```
chad-development-dashboard/
│
├── index.html                      # Complete dashboard (single file)
├── chad_inseed_master_dataset.csv  # Integrated master dataset
└── README.md
```

---

## 🏛️ Data Sources

All data is sourced exclusively from official Chad government statistics:

| Source | Description | URL |
|--------|-------------|-----|
| **INSEED Chad** | Institut National de la Statistique | [inseed.td](https://www.inseed.td) |
| **Chad Data Portal** | Official open data portal | [chad.opendataforafrica.org](https://chad.opendataforafrica.org) |

### Datasets Used
- Health & Nutrition indicators (1996–2018)
- Vaccination coverage rates (1996–2018)
- Disease prevalence (1996–2018)
- Demographic indicators (1993–2019)
- Food security by region (2016–2024)
- GDP — Expenditure approach (2005–2022)
- GDP — Production approach (2005–2022)
- Real income by region (2005–2021)
- Employment & poverty (2003–2018)
- Unemployment (2003–2018)
- Imports (2004–2020)
- Exports non-oil (2004–2020)

---

## 🔧 Technology

Built with pure web standards — no frameworks, no build tools:

- **HTML5** — structure and layout
- **CSS3** — dark theme, responsive grid
- **Vanilla JavaScript** — tab switching and interactivity
- **Chart.js 4.4** — line, bar, and doughnut charts (CDN)

Single file deployment — works offline, no dependencies to install.

---

## 🔭 Future Work

- [ ] Add agricultural statistics by region (Ministry of Agriculture)
- [ ] Integrate health yearbooks 2019–2023 (INSEED)
- [ ] Add conflict/fragility index overlay
- [ ] Regional disaggregation maps
- [ ] French language toggle
- [ ] Automated data refresh pipeline

---

## 🔗 Related Projects

Part of an integrated data science portfolio focused on Chad and Sub-Saharan Africa:

| Project | Description |
|---------|-------------|
| [Child Malnutrition Prediction](https://github.com/Derio001/chad-malnutrition-prediction) | 92% accuracy ML model + live Streamlit app |
| [LRI Risk Prediction](https://github.com/Derio001/lri-prediction-chad) | Respiratory infection risk in Chadian children |
| [Crop Yield Early Warning](https://github.com/Derio001/Chad-crop-yield-prediction) | 43 years FAO + NASA data, XGBoost model |
| [GDP Intelligence](https://github.com/Derio001/exploratory-predictive-gdp-analysis) | 180+ countries, Power BI dashboard |

---

## 👤 Author

**Mahamat Hanga Derio**  
M.Tech Data Science — Christ University, Bangalore  
Chadian national | Building ML tools for public health and development in Africa

📬 Open to collaboration with UNICEF, WFP, FAO, World Bank, and research 
institutions working on development in Chad and the Sahel.

🔗 [GitHub](https://github.com/Derio001) | 
[Malnutrition App](https://chad-malnutrition-app-tnkhzrgg9pbme32naw5cxg.streamlit.app)

---

*Built using official data from INSEED Chad — Institut National de la Statistique, 
des Études Économiques et Démographiques.*
