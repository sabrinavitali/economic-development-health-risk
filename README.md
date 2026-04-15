# economic-development-health-risk
Analysis of how economic development reshapes health risk across the life cycle, focusing on early-life and behavioural risk using global data.
# Global Risk Across the Life Cycle

## Overview

This project analyzes how economic development reshapes the distribution of health risk across the life cycle.

Rather than focusing only on mortality levels, the analysis explores how risk changes in nature as countries develop — shifting from early-life survival risks to behavioural risks during adolescence.

## Key Question

Does economic development reduce risk, or does it transform it?

## Indicators

The analysis is based on two main indicators:

- **Early-Life Risk** → proxied by neonatal mortality (share of deaths within the first 28 days of life)
- **Behavioural Risk** → proxied by adolescent alcohol consumption (ages 15–19)

These indicators capture different dimensions of risk occurring at different stages of life.

## Methodology

- Data collected from international sources (e.g., UNICEF, World Bank)
- Data cleaning and transformation performed using **Polars**
- Visualizations created using **Plotnine**
- GDP per capita used as a proxy for economic development

The analysis focuses primarily on **2016** as a benchmark year, with additional time-series exploration.

## Key Insights

- Risk does not disappear with development — it **shifts across the life cycle**
- Higher-income countries show a greater concentration of **early-life risk**, reflecting structural limits of healthcare
- Lower-income countries experience more **distributed mortality** across early childhood
- Behavioural risk increases with GDP, particularly during adolescence
- Development changes not only the level of risk, but its **structure**

## Repository Structure

- `report.qmd` → main analysis and narrative  
- `report.html` → final rendered output  
- `data/` → datasets used for the analysis  
- `code/` → data preparation and visualization scripts  

## Author

Sabrina Vitali
