# Global AI Workforce Insights Dashboard

An end-to-end data-driven case study and interactive Tableau dashboard exploring AI workforce trends, inequities, and opportunities across industries, geographies, and roles from 2020–2025.

## 🚀 Features

- **Data Integration**  
  - Blends 93,597 records from a primary Kaggle “AI Job Market Trends & Salaries” CSV with two secondary enrichment datasets  
  - Cleans, encodes, and joins all sources using Tableau Prep Builder

- **Interactive Tableau Story**  
  - Multi-panel salary Pareto charts, remote-work ratio comparisons, skill-demand maps, funnel and gender-pay donut visualizations  
  - Filters by Year, Industry, Job Title, Country, Company Size, and Remote-Friendly status  
  - Executive “Recommendations & Call to Action” overlay for HR strategy

- **Statistical & Visual Analysis**  
  - t-tests and ANOVA on key factors  
  - Identification of pay inequities, mid-level progression bottlenecks, and regional skill gaps  

## 📂 Repository Structure

```text
├── data/
│   ├── main_ai_salaries.csv
│   ├── ai_job_market_insights.csv
│   └── salary_demographics.csv
├── prep/
│   └── tableau_prep_flow.tfl
├── tableau/
│   └── Global_AI_Workforce_Story.twbx
├── README.md
└── LICENSE
